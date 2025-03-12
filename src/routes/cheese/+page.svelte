<main>
  <div class="background">
    <div class = "Nav">
     <nav>
      <a href="/">Home</a>
      <a href="/pirate">Pirate</a>
      <a href="/cheese">Cheese</a>
      <a href="/cupcake">Cupcake</a>
      <a href="/hipster">Hipster</a>
     </nav>
    </div>
    <div class= "header">
    <h2>Pee-YOO Cheese Ipsum</h2>
    </div>
<div class = "text">
    <p>
      Cheesy grin parmesan taleggio. Brie boursin pecorino cheesy feet taleggio
      hard cheese roquefort when the cheese comes out everybody's happy. St.
      agur blue cheese port-salut bocconcini cheesecake rubber cheese mozzarella
      stilton cheese strings. Bocconcini.
    </p>

    <p>
      Fromage the big cheese camembert de normandie. Cut the cheese gouda brie
      the big cheese when the cheese comes out everybody's happy squirty cheese
      cut the cheese gouda. Boursin cottage cheese cheeseburger camembert de
      normandie cheese slices goat port-salut danish fontina. Emmental
      caerphilly cream cheese mozzarella camembert de normandie cheesy feet.
    </p>
    </div>
  </div>
</main>

<style>
  p {
    font-family: "Lobster", sans-serif;
    font-weight: 400;
    font-style: normal;
  }
  h2 {
    font-family: "Pacifico", sans-serif;
    font-weight: 400;
    font-style: normal;
    font-size: 400%;
    color: #E1BD54;
  }
  .background {
    background-image: url("/Cheese-background.jpg");
    padding-bottom: 40%;
    background-repeat: no-repeat;
    align-items: center;
    align-self: center;
    display: grid;
    grid: " n    n    n  " 5vh
          " .    .    .  " 5vh
          " .    h    .  " 10vh
          " .    t    .  " 50vh
          / 1fr  5fr  1fr;
  }
  main {
    background-color: #FFE07D;
    align-items: center;
  }
  .header{
    background-color: #FFE899;
    grid-area: h;
    margin-top: 3%;
    text-align: center;
  }
  .text{
    margin-top:33%;
    grid-area: t;
    rotate: -25deg;
    margin-left:25%;
    margin-right:50%;
    font-size: xx-small;
    transition: 0.5s;
  }
  .Nav{
    grid-area: n;
    padding: 1%;
    background-color: #E1BD54;
    text-align: center;
    margin-top: 0%;
  }
  a{
    text-decoration: none;
    font-family: "Lobster", sans-serif;
    color: black;
    margin: 2%;
  }
  .text:hover{
    font-size: medium;
    rotate: 0deg;
    padding: 2%;
    margin: 5%;
    margin-top: 10%;
    background-color: rgb(247, 237, 204, 0.6);
    transition: 0.5s;
    margin-bottom: 10%;
  }
</style>
