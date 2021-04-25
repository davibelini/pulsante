<script>
  export let links
</script>

<main>
  <nav class="header-nav">
    {#each links as link}
      <a href="#{link}" class="link">{link}</a>
    {/each}
  </nav> 
</main>

<style>
  main {
    position: default;
  }
  .header-nav {
    display: flex;
    justify-content: flex-start;
    margin-left: 100px;
  }
  .link {
    font-family: 'IBM Plex Serif';
    margin: 0px 50px;
    color: rgb(2, 31, 18);
    z-index: 0;
  }
</style>