<script>
    import Title from "./Contents/Title.svelte";
    import Description from "./Contents/Description.svelte";
import MusicCard from "./Contents/MusicCard.svelte";
import ButtonProceed from "./Contents/ButtonProceed.svelte";
</script>
<div class="container">
  <Title>
      Order Summary
  </Title>
  <Description/>
  <MusicCard/>
  <ButtonProceed/>
  <div class="cancel">Cancel Order</div>
</div>

<style>
  .cancel{
    padding: 10px;
  }
  .cancel:hover{
    cursor: pointer;
  }
  .container {
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: white;
    padding: 20px;
  }
</style>
