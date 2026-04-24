<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Parallax Website</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
    }

    /* Parallax Sections */
    .parallax {
      position: relative;
      min-height: 100vh;
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .parallax-1 {
      background-image: url("https://images.unsplash.com/photo-1501785888041-af3ef285b470");
    }

    .parallax-2 {
      background-image: url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee");
    }

    .parallax-3 {
      background-image: url("https://images.unsplash.com/photo-1493244040629-496f6d136cc3");
    }

    /* Text on Image */
    .overlay-text span {
      background: rgba(0, 0, 0, 0.6);
      color: #fff;
      padding: 15px 25px;
      font-size: 28px;
      letter-spacing: 2px;
      border-radius: 5px;
    }

    /* Content Sections */
    .content {
      padding: 60px 80px;
      text-align: center;
    }

    .content h2 {
      margin-bottom: 20px;
      font-size: 32px;
    }

    .content p {
      font-size: 16px;
      max-width: 800px;
      margin: auto;
    }

    .light {
      background: #f4f4f4;
      color: #333;
    }

    .dark {
      background: #333;
      color: #fff;
    }

    /* Mobile Fix (Parallax doesn't work well on mobile) */
    @media (max-width: 768px) {
      .parallax {
        background-attachment: scroll;
      }
    }
  </style>
</head>

<body>

  <section class="parallax parallax-1">
    <div class="overlay-text">
      <span>Parallax Website</span>
    </div>
  </section>

  <section class="content light">
    <h2>Section One</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam aut amet
      odio est laborum obcaecati perferendis! Mollitia officiis, consectetur vitae
      laborum eos expedita reprehenderit nostrum tempore.
    </p>
  </section>

  <section class="parallax parallax-2">
    <div class="overlay-text">
      <span>Explore Nature</span>
    </div>
  </section>

  <section class="content dark">
    <h2>Section Two</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam aut amet
      odio est laborum obcaecati perferendis! Mollitia officiis, consectetur vitae
      laborum eos expedita reprehenderit nostrum tempore.
    </p>
  </section>

  <section class="parallax parallax-3">
    <div class="overlay-text">
      <span>Look Deep Into Nature</span>
    </div>
  </section>

  <section class="content dark">
    <h2>Section Three</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam aut amet
      odio est laborum obcaecati perferendis! Mollitia officiis, consectetur vitae
      laborum eos expedita reprehenderit nostrum tempore.
    </p>
  </section>

  <section class="parallax parallax-1">
    <div class="overlay-text">
      <span>Do Some Coding</span>
    </div>
  </section>

</body>
</html>
