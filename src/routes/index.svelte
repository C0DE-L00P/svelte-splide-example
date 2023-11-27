<script >
  import '@splidejs/splide/dist/css/splide.min.css';
  import BasicExample from './components/BasicExample.svelte';
  import DynamicSlidesExample from './components/DynamicSlidesExample.svelte';
  import ThumbnailsExample from './components/ThumbnailsExample.svelte';
  // import AutoplayExample from './components/AutoplayExample.svelte';
  // import ReactivityExample from './components/ReactivityExample.svelte';
  // import VideoExample from './components/VideoExample.svelte';
</script>

<main>
  <BasicExample/>
  <hr>
  <DynamicSlidesExample/>
  <hr>
  <ThumbnailsExample/>
  <hr>
  <!-- <ReactivityExample/>
    <hr>
    <AutoplayExample/>
  <hr>
  <VideoExample/> -->
</main>

<style global>
  body {
    font-family: 'Poppins', sans-serif;
    padding: 5rem 0;
  }

  h1 {
    text-align: center;
  }

  hr {
    width: 200px;
    max-width: 50%;
    margin: 4rem auto;
  }

  button {
    font-family: inherit;
  }

  .wrapper {
    max-width: 600px;
    margin: 0 auto;
  }

  .splide__slide {
    background: #eee;
  }

  .splide__slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .splide--nav {
    margin-top: 1rem;
  }
</style>