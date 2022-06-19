<script>
import Bulma from "bulma";
import Header from "$lib/Header.svelte";
import Footer from "$lib/Footer.svelte";
</script>


<Header />
<div class="container">
  <slot />
</div>
<Footer />