<script>
  import { Router, Link, Route } from "svelte-routing";
  import Register from "./routes/Register.svelte";
  import Login from "./routes/Login.svelte";


  export let url = "";
</script>

<main>

</main>

<Router url="{url}">

  <div>
    <Route path="/register"><Register /></Route>
    <Route path="/login"><Login /></Route>
  </div>


</Router>