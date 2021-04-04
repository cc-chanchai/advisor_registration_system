<template>
  <div>
    <nav
      class="navbar is-link is-fixed-top"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="navbar-brand">
        <a
          class="navbar-item"
          href="http://eng.sut.ac.th/cpe/cpesut/webcpe/"
          target="_blank"
        >
          <img src="@/assets/logo-cpe.png" alt="CPE logo" />
        </a>

        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <!-- <a class="navbar-item">
        Home
      </a> -->

          <router-link class="navbar-item" to="/"> Home </router-link>
          <router-link class="navbar-item" to="/"> Advisor Profiles </router-link>
          <router-link class="navbar-item" to="/"> Report an issue </router-link>
        

          <!-- <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link"> More </a>

            <div class="navbar-dropdown">
              <a class="navbar-item"> About </a>
              <a class="navbar-item"> Jobs </a>
              <a class="navbar-item"> Contact </a>
              <hr class="navbar-divider" />
              <a class="navbar-item"> Report an issue </a>
            </div>
          </div> -->
        </div>

        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <router-link to="/signUp">
                <a class="button is-primary">
                  <strong>Sign up</strong>
                </a>
              </router-link>
              
              <router-link to="/login" >
                <a class="button is-light">
                  <strong>Sign in</strong>
                </a> 
              </router-link>
              <!-- <a class="button is-light">
                <router-link to="/login"> Sign in </router-link>
              </a> -->
            </div>
          </div>
        </div>
      </div>
    </nav>
    <hr />
    <hr />
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>