<script>
  import { Link } from "svelte-navigator";
  import About from "../pages/About.svelte";
  import Home from "../pages/Home.svelte";
  import Contact from "../pages/Contact.svelte";
</script>

<nav >
  <div class="left" />

  <div class="center" />
  <Link to="/">Home</Link>
  <Link to="about">About</Link>
  <Link to="contact">Contact</Link>
  <div class="right" />
</nav>

<style>
  .center {
    display: flex;
    justify-content: space-between;
    justify-content: end;
  }
</style>
