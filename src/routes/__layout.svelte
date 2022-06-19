<script>
import Header from "$lib/Header.svelte";
import Footer from "$lib/Footer.svelte";
</script>

<svelte:head>
  <meta name="robots" content="noindex" />
  <title>Title</title>
  <link rel="stylesheet" href="global.css" />
  <script
    src="https://kit.fontawesome.com/a3e38f6c6f.js"
    crossorigin="anonymous"></script>
</svelte:head>

<Header />
<div class="container has-background-primary">
  <slot />
</div>
<Footer />

