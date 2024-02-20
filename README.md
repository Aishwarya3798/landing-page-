<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Flower Shop Landing Page</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header id="header">
      <div class="header-content-div">
        <a href="#home-sec">
          <img
            src="https://s.tmimgcdn.com/scr/1200x627/212800/lotus-flower-colorful-logo_212825-original.png"
            alt="Company Logo"
            id="header-img"
        /></a>
        <strong><h1>Colorful</h1></strong>
        <nav id="nav-bar">
          <a href="#about" class="nav-link">ABOUT</a>
          <a href="#varieties" class="nav-link">VARIETIES</a>
          <a href="#our-service" class="nav-link">OUR SERVICE</a>
        </nav>
      </div>
    </header>
    <main>
      <section id="home-sec" class="flexible home-sec">
        <div class="eye-grabber-img">
          <img src="https://images.unsplash.com/photo-1596073419667-9d77d59f033f?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cm9zZSUyMGZsb3dlcnxlbnwwfHwwfHx8MA%3D%3D=" alt="Image of flower" />
        </div>
        <div class="eye-grabber">
          <h1>Fresh, Beautiful.</h1>
          <h2>
            National Rose Garden is one of the rose gardens of India.
          </h2>
          <button class="btn" onclick="window.location.href = '#contact';">
            Buy Now
          </button>
        </div>
      </section>
      <section id="about" class="sec-padding">
        <h3 class="section-heading">ABOUT US</h3>
        <div class="sec-content-div flexible">
          <p>
            We are a group of people with decades of experience in growing and
            selling rose. We know what a good rose looks like and how they
            are grown.  It describes the speaker's deep love for his or her beloved and promises that this love will last longer than human life and even the planet itself, remaining fresh and constant forever.
          <img src="https://images.fineartamerica.com/images/artworkimages/mediumlarge/3/group-of-rose-deepak-vt.jpg" alt="rose image" />
        </div>
      </section>
      <section id="varieties" class="sec-padding">
        <h3 class="section-heading">VARIETIES</h3>
        <div class="sec-content-div flexible">
          <div class="tile">
            <img src="https://a-z-animals.com/media/2023/07/shutterstock-18299716-huge-licensed-scaled.jpg" alt="photo of Double Delight Rose" />
            <h4>Double Delight Rose</h4>
            <p>
               It is a multiple award-winning, red blend hybrid tea rose cultivar bred in the United States by Swim & Ellis and introduced in 1977. 
            </p>
          </div>
          <div class="tile">
            <img
              src="https://a-z-animals.com/media/2022/12/shutterstock_1745247305-1024x683.jpg"
              alt="photo of Darcey Rose"
            />
            <h4>Darcey Rose</h4>
            <p>
               Darcey is awash with raspberry red and rich berry tones and proves popular for both summer and winter events.
            </p>
          </div>
          <div class="tile">
            <img src="https://a-z-animals.com/media/2023/07/shutterstock-2225406157-huge-licensed-scaled.jpg" alt="photo of Black Baccara Rose" />
            <h4>Black Baccara Rose</h4>
            <p>
              It has a high-centered, very full (41+ petals) bloom form. The flowers are dark red-burgundy with a velvety texture.
            </p>
          </div>
          <div class="tile">
            <img src="https://a-z-animals.com/media/2023/07/shutterstock-1893356350-huge-licensed-scaled.jpg" alt="photo of Gold Medal Rose" />
            <h4>Gold Medal Rose</h4>
            <p>
               High-centered, reflexed, deep golden-yellow flowers (40 petals), brushed copper-orange when they open.
            </p>
          </div>
          <div class="tile">
            <img src="https://a-z-animals.com/media/2022/12/shutterstock_1581865033-1024x683.jpg" alt="photo of Rhapsody In Blue Rose" />
            <h4>Rhapsody In Blue Rose</h4>
            <p>
              Blue is a tall, bushy shrub rose boasting very fragrant, cupped, semi-double (16 petals), iridescent purple flowers fading to mauve-gray.
            </p>
          </div>
          <div class="tile">
            <img src="https://a-z-animals.com/media/2023/07/shutterstock-2111447792-huge-licensed-scaled.jpg" alt="photo of Winchester Cathedral Rose" />
            <h4>Winchester Cathedral Rose</h4>
            <p>
              A white sport of 'Mary Rose', with the occasional touch of pink. It produces a mass of medium-sized, loose petalled, fragrant rosettes, and continues to bloom at regular intervals throughout the summer.
            </p>
          </div>
        </div>
      </section>
      <section id="our-service" class="sec-padding">
        <h3 class="section-heading">OUR SERVICE</h3>
        <div class="sec-content-div">
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/w6H542X/Fresh.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Fresh</h5>
              <p>We deliver fresh Roses with a 100% guarantee of freshness.</p>
            </div>
          </div>
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/FKNq4Qr/delivered.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Fast</h5>
              <p>
                We deliver your orders as fast as possible, delivery procedure
                begins as soon as apple is plucked from tree.
              </p>
            </div>
          </div>
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/HHQK1wV/happy.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Satisfying</h5>
              <p>
                We guarantee 100% customer satisfaction. We do our best to make
                your purchase experience smooth. But if we mess up somehow you
                will get compensated for every inconvenience.
              </p>
            </div>
          </div>
        </div>
      </section>
     <section class="sec-padding" id="contact">
        <h3 class="section-heading">CONTACT</h3>
        <div class="sec-content-div flexible">
          <h6>To make an order or just to know more contact us : aishwarya@gmail.com</h6>
          </form>
        </div>
      </section>
    </main>
    <footer>
      Created by
      <a href="#">Aishwarya </a>
    </footer>
  </body>
</html>
