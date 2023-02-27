<!-- page.svelte -->
<script>
    import Footer from "./Footer.svelte";
import Hero from "./Hero.svelte";
  import Marketing from "./Marketing.svelte";
  </script>
  
  <Hero />
  <Marketing title="Hello" />
  <Marketing title="Hello" />
  <Marketing title="Hello" />
  <Footer />

  
  <style>
    :global(html,body) {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  </style>
  