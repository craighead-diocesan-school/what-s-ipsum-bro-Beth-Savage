<script>
	let y
	let height
	$: scrollPercentage = y / (1500 - height)
</script>
<svelte:window bind:scrollY={y} bind:innerHeight={height}/>
<main>
  <div class = "nav">
    <nav>
      <a href="pirate">Pirate</a>
      <a href="cheese">Cheese</a>
      <a href="cupcake">Cupcake</a>
      <a href="hipster">Hipster</a>
    </nav>
    <div class ="cupcake">
      <img src="scroll-cupcake.png" alt="Cupcake" /> 
      {#if scrollPercentage > 0.1 }
      <div class="sprinkle first"></div>
      {/if}
      {#if scrollPercentage > 0.2 }
      <div class="sprinkle second"></div>
      {/if}
      {#if scrollPercentage >  0.3}
      <div class="sprinkle third"></div>
      {/if}
      {#if scrollPercentage >  0.4}
      <div class="sprinkle forth"></div>
      {/if}
      {#if scrollPercentage >  0.5}
      <div class="sprinkle fifth"></div>
      {/if}
      {#if scrollPercentage >  0.6}
      <div class="sprinkle sixth"></div>
      {/if}
      {#if scrollPercentage >  0.7}
      <div class="sprinkle seventh"></div>
      {/if}
      {#if scrollPercentage >  0.8}
      <div class="sprinkle eighth"></div>
      {/if}
      {#if scrollPercentage >  0.9}
      <div class="sprinkle ninth"></div>
      {/if}

    </div>
  </div>
  <div class="background">
    <div class="header">
      <h2>Yum Cupcake Ipsum</h2>
    </div>
    <div class = "text">
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>  
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>  
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p>   
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p> 
     <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate.
     </p>

     <p>
      Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate
      bar sweet roll macaroon soufflé powder sugar plum tart.
     </p> 
     
   </div>
  </div>
</main>
<style>
   .sprinkle {
    position: fixed;
    width: 5px;
    height: 5px;
    border-radius: 50%;
  }

  .first {
    background-color: yellow;
    bottom: 12vh;
    right: 5vw;
  }
  .second {
    background-color: greenyellow;
    bottom: 11vh;
    right: 7.7vw;
  }
  .third {
    background-color: red;
    bottom: 11.5vh;
    right: 10vw;
  }
  .forth{
    background-color: blue;
    bottom: 14vh;
    right: 6vw;
  }
  .fifth{
    background-color: yellow;
    bottom: 14vh;
    right: 9vw;
  }
  .sixth{
    background-color: greenyellow;
    bottom: 15vh;
    right: 3vw;
  }
  .seventh{
    background-color: red;
    bottom: 17vh;
    right: 4.5vw;
  }
  .eighth{
    background-color: blue;
    bottom: 17.5vh;
    right: 7.7vw;
  }
  .ninth{
    background-color: yellow;
    bottom: 21vh;
    right: 6vw;
  }

  .background{
    background-color: #F7BDB0; 
    align-items: center;
    grid-area: b;
    display: grid;
    grid: " .    h    .  " 10vh
          " .    p    .  " 290vh
          / 1fr  5fr  1fr;
  }
  .nav{
    background-color: #F5E392;
    grid-area: n;
    align-items: center;
  }
  nav a{
    display: flex;
    margin:1%;
    font-family:"Oleo Script", system-ui ;
    color: black;
    font-size: 200%;
    margin-right: 10%;
  }
  main{
    display: grid;
    grid: " b    b    n  " 100vh
          " b    b    n  " 100vh
          " b    b    n  " 100vh
          / 1fr  5fr  1fr;
  }
  p{
    font-family: "Oleo Script", system-ui;
    font-size: larger;
  }
  h2{
    color: #E42357;
    font-size: 400%;
    font-family: "Mystery Quest", system-ui;
    grid-area: h;
    text-align: center;
  }
  .text{
    grid-area: p;
    margin-right: 10%;
    margin-left: 10%;
  }
  .header{
    grid-area: h;
    margin-top: 5%;
  }
  img{
    width: 100%;
    height: auto;
  }
  .cupcake{
    position: fixed;
    bottom:0;
    right:0;
    width:13%;
  }
</style>
