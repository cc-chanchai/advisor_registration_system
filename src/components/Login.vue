<template>
  <div class="columns">
    <div class="column"></div>
    <!-- <section>
      <div id="login" class="card">
        <header class="card-header is-primary">
          <p class="card-header-title">LOGIN</p>
        </header>
        <div class="card-content">
          <div class="content">
            <div class="container">
              <div class="field">
                <p class="control has-icons-left has-icons-right">
                  <input class="input" type="email" placeholder="Email" />
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
                  <input class="input" type="password" :value="password" placeholder="Password" />
                  <span class="icon is-small is-left">
                    <i class="fas fa-lock"></i>
                  </span>
                </p>
              </div>
              <b-checkbox>Remember me</b-checkbox>
              <div class="field">
                <p class="control">
                  <button class="button is-success">Login</button>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <br />

    <section id="login">
      <form class="box">
        <div class="field">
          <label class="label">Email</label>
          <div class="control">
            <input
              class="input"
              type="email"
              placeholder="e.g. alex@example.com"
            />
          </div>
        </div>

        <div class="field">
          <label class="label">Password</label>
          <div class="control">
            <input class="input" type="password" placeholder="********" />
          </div>
        </div>

        <button class="button is-primary">Sign in</button>
      </form>
    </section> -->
    <div id="login" class="column is-one-quarter">
      <section class="section">
        <form action="">
          <div class="panel is-primary" style="width: auto">
            <div class="panel-heading">
              <p>Login</p>
            </div>
            <section>
              <div class="column">
                <b-field label="Email">
                  <b-input
                    type="email"
                    :value="email"
                    placeholder="Your email"
                    required
                  >
                  </b-input>
                </b-field>
              </div>
              <div class="column">
                <b-field label="Password">
                  <b-input
                    type="password"
                    :value="password"
                    password-reveal
                    placeholder="Your password"
                    required
                  >
                  </b-input>
                </b-field>
              </div>
              <div class="column">
                <b-checkbox>Remember me</b-checkbox>
              </div>
            </section>
            <div class="column content has-text-right">
                <b-button label="Login" type="is-primary" />
            </div>
          </div>
        </form>
      </section>
    </div>
    <div class="column"></div>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#login {
  /* list-style-type: none; */
  /* padding: 0; */
  /* display: inline-flex; */
  /* margin: 0 100; */

  text-align: left;
}
</style>
