<script>
  import LinkArea from "./LinkArea.svelte"
</script>

<main>
  <header class="top">
    <LinkArea links={["comprar", "carrinho", "produtos"]}></LinkArea>
    <!--<img src="/assets/pulseira.jpg" alt="Foto de pulseira." class="image">--> <!--doesnt work-->
  </header>
</main>

<style>
  main {
    display: flex;
    align-items: center;
    height: 65px;
    width: 100vw;
  }
  .top::before {
    box-shadow: inset 0 0 2000px rgba(255, 255, 255, 0.5);
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    filter: blur(10px);
    z-index: -2;
  }
</style>