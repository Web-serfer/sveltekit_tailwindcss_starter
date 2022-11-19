<script>
  import "../app.css";
  import Header from "../libs/components/Header.svelte";
  import Footer from "../libs/components/Footer.svelte";
</script>

<div class="bg-slate-100">
  <Header />
    <slot />
  <Footer />
</div>

