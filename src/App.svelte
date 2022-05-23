<script>
  import { Router, Route } from "svelte-navigator";
  import Navbar from "./component/Navbar.svelte";
  import About from "./pages/About.svelte";
  import Home from "./pages/Home.svelte";
</script>

<Router primary={false}>
  <Navbar />
  <main>
    <Route path="/">
      <Home />
    </Route>

    <Route path="/about">
      <About />
    </Route>
  </main>
</Router>

<style>
  @media (max-width: 575.98px) {
  }

  @media (max-width: 767.98px) {
  }

  @media (max-width: 991.98px) {
  }

  @media (max-width: 1199.98px) {
  }

  @media (max-width: 1399.98px) {
  }
</style>
