<template>
<section class="section">

  <div id="login" class="card">
  <header class="card-header">
    <p class="card-header-title">
      LOGIN
    </p>
    
  </header>
  <div class="card-content">
    <div class="content">
      <div class="container">
  <div class="field ">
  <p class="control has-icons-left has-icons-right">
    <input class="input" type="email" placeholder="Email">
    <span class="icon is-small is-left">
      <i class="fas fa-envelope"></i>
    </span>
    <span class="icon is-small is-right">
      <i class="fas fa-check"></i>
    </span>
  </p>
</div>
<div class="field">
  <p class="control has-icons-left">
    <input class="input" type="password" placeholder="Password">
    <span class="icon is-small is-left">
      <i class="fas fa-lock"></i>
    </span>
  </p>
</div>
<div class="field">
  <p class="control">
    <button class="button is-success">
      Login
    </button>
  </p>
</div>
</div>
    </div>
  </div>
</div>
  
</section>
  
<!-- <div class="container is-widescreen">
  <div class="notification is-primary">
    This container is <strong>fullwidth</strong> <em>until</em> the <code>$widescreen</code> breakpoint.
  </div>
</div> -->

<!-- <section id="login">
<form class="box">
  <div class="field">
    <label class="label">Email</label>
    <div class="control">
      <input class="input" type="email" placeholder="e.g. alex@example.com">
    </div>
  </div>

  <div class="field">
    <label class="label">Password</label>
    <div class="control">
      <input class="input" type="password" placeholder="********">
    </div>
  </div>

  <button class="button is-primary">Sign in</button>
</form>
</section> -->
</template>

<script>
export default {
  name: "Login"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#login {

  list-style-type: none;
  padding: 0;
  display: inline-block;
  margin: 0 100;
  
  text-align: left;
}
</style>
