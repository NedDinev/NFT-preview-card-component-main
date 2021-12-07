<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
      crossorigin="anonymous"
    />

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | NFT preview card component</title>
  </head>

  <body>
    <div class="card mx-auto px-4 py-4 my-5">
      <a href="#">
        <div class="NFT_overlay d-flex">
          <i class="fas fa-eye mx-auto my-auto"></i>
        </div>
        <img src="images/image-equilibrium.jpg" alt="NFT" class="NFT d-flex" />
      </a>

      <h5 class="card-title my-4"><a href="#">Equilibrium #3429</a></h5>

      <p class="card-subtitle mb-4">
        Our Equilibrium collection promotes balance and calm.
      </p>
      <div class="card-text d-flex justify-content-between">
        <p class="price"><i class="fab fa-ethereum"></i> 0.041 ETH</p>
        <p class="days-left"><i class="fas fa-clock"></i> 3 days left</p>
      </div>
      <hr />
      <div class="card-text d-flex">
        <a href="#"
          ><img src="images/image-avatar.png" alt="user" class="user"
        /></a>
        <p class="creator mx-3">
          Creation of
          <a href="#">Jules Wyvern</a>
        </p>
      </div>
    </div>

    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="https://github.com/NedDinev">NedDinev</a>.
    </div>
  </body>
</html>
