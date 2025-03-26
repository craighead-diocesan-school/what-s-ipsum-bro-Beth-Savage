<main>
  <header>
    <h2>You Probably Haven't Heard of Hipster Ipsum</h2>
  </header>
  <nav>
    <a href="/">Home</a>
    <a href="pirate">Pirate</a>
    <a href="cheese">Cheese</a>
    <a href="cupcake">Cupcake</a>
    <a href="hipster">Hipster</a>
  </nav>
  <article>
    <p>
      Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan
      craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester
      paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food
      truck kale chips pabst, bitters raw denim artisan waistcoat seitan
      freegan.
    </p>
    <p>
      Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo
      booth listicle fam truffaut subway tile yr cred chicharrones semiotics
      biodiesel green juice microdosing whatever. Truffaut praxis PBR and B
      tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut
      kitsch pop-up. Letterpress street art mlkshk marxism.
    </p>
  </article>
</main>

<style>
  main {
    background-image: url("/Cafe-background.png");
    background-repeat: no-repeat;
    background-size: 100% auto;
    height: 220vh;
    width: 99vw;
    display: grid;
    grid:
      " .    .    n  " 50vh
      " h    h    .  " 50vh
      " .    a    .  " 120vh
      / 2fr 3fr 3fr;
  }
  header {
    grid-area: h;
    rotate: -22.5deg;
    margin-top: 23%;
    margin-left: 10%;
    opacity: 5%;
    transition: 0.5s;
  }
  header:hover {
    opacity: 100%;
    transition: 0.5s;
  }
  nav {
    grid-area: n;
    margin-top: 30%;
    margin-left: 13%;
    opacity: 5%;
    transition: 0.5s;
  }
  nav:hover {
    opacity: 100%;
    transition: 0.5s;
  }
  article {
    grid-area: a;
    margin-top: 60%;
    margin-left: 20%;
    margin-right: 10%;
    font-family: "Kaushan Script", cursive;
    font-weight: 400;
    opacity: 5%;
    font-size: 0.8rem;
    transition: 0.5s;
    padding-top: 20%;
  }
  article:hover {
    opacity: 100%;
    font-size: 1.2rem;
    transition: 0.5s;
    margin-left: 10%;
    margin-right: 0%;
  }
  h2 {
    font-family: "Zen Tokyo Zoo", system-ui;
    font-weight: 400;
    font-size: 3rem;
  }
  a {
    font-family: "Kaushan Script", cursive;
    font-weight: 400;
    color: white;
    display: flex;
    margin: 2%;
    font-size: 1.2rem;
  }
</style>
