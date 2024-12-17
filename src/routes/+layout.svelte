<script>
  import '$lib/global.css';
  import { MakeItSnow, Footer, Header } from '$lib'

  let { children } = $props()
</script>

<Header />

{@render children()}

<Footer />

<MakeItSnow count=1000 />