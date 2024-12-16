<script>
   import { MakeItSnow, Footer, Header } from '$lib'

   	let { children } = $props()
</script>

<Header />

{@render children()}

<Footer />

<MakeItSnow/>

<style>
  :global(body) {
    color: #fff;
    background-color: #000;
    background-image: linear-gradient(to bottom, #000, #050505);
  }
</style>