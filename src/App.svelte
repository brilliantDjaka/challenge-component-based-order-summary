<script>
  import Footer from './Apps/Footer.svelte';
  import HeaderImage from './Apps/HeaderImage.svelte';
  import Content from './Apps/Content.svelte';
</script>

<main>
  <div class="container">
    <HeaderImage />
    <Content />
  </div>

  <Footer />
</main>

<style>
  .container {
    width: 350px;
    border-radius: 15px;
    text-align: center;
  }
  main {
    padding: 50px;
    display: grid;
    justify-content: center;
    background-color: hsl(225, 100%, 94%);
  }
</style>
