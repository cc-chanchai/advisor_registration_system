<template>
  <div class="columns">
    <div class="column"></div>
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
