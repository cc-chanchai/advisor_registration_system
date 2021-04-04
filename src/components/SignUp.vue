<template>
  <section>
        
        <div id="form" class="columns">
          <div class="column"></div>
          <b-field position="is-centered">
          <b-input placeholder="Search..." type="search" icon="magnify">
          </b-input>
          <p class="control">
            <b-button label="Submit" type="is-info" />
          </p>
        </b-field>
          <div class="column"></div>
        </div>
     
        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field
              label="Username"
              :label-position="labelPosition"
              type="is-success"
              message="This username is available"
            >
              <b-input disabled value="johnsilver" maxlength="30"></b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div>

        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field
              label="Password"
              :label-position="labelPosition"
              type="is-warning"
            >
              <b-input value="123" type="password" maxlength="30"></b-input>
              <template #message>
                <div>Password is too short</div>
                <div>Password must have at least 8 characters</div>
              </template>
            </b-field>
          </div>
          <div class="column"></div>
        </div>

        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field label="Name" :label-position="labelPosition">
              <b-input value="Kevin Garvey"></b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div>

        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field
              label="Email"
              :label-position="labelPosition"
              type="is-danger"
              message="This email is invalid"
            >
              <b-input type="email" value="john@" maxlength="30"> </b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div>
    
        <!-- <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field
              label="Username"
              :label-position="labelPosition"
              type="is-success"
              message="This username is available"
            >
              <b-input disabled value="johnsilver" maxlength="30"></b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div>

        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field label="Name" :label-position="labelPosition">
              <b-input disabled value="Kevin Garvey"></b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div>

        <div id="form" class="columns">
          <div class="column"></div>
          <div class="column is-one-quarter">
            <b-field
              label="Email"
              :label-position="labelPosition"
              type="is-danger"
              message="This email is invalid"
            >
              <b-input disabled type="email" value="john@" maxlength="30">
              </b-input>
            </b-field>
          </div>
          <div class="column"></div>
        </div> -->
        <b-button type="is-primary">Submit</b-button>
  </section>
</template>

<script>
export default {
  name: "SignUp",
};
</script>

<style>
#form {
  /* list-style-type: none; */
  /* padding: 0; */
  /* display: flex; */
  /* margin: 0 100; */

  text-align: left;
}
</style>