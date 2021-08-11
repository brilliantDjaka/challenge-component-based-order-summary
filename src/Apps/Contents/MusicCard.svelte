<script>
  import Logo from './MusicCards/Logo.svelte';
  import Content from './MusicCards/Content.svelte';
</script>

<div class="container">
  <Logo />
  <Content/>
  <div style="padding-right: 40px;"></div>
  <p><a class="change" href="/">Change</a></p>
</div>

<style>
  .change{
    text-decoration: underline;
  }
  .container {
    align-items: center;
    margin-top: 20px;
    padding: 10px;
    background-color: #f8f9fe;
    display: flex;
    flex-direction: row;
    border-radius: 10px;
  }
</style>
