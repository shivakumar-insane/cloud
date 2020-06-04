<template>
  <div>
    <b-tabs content-class="mt-3" fill>
      <b-tab title="Home" active>
        <h2>WELCOME TO INSANE ANALYTICS</h2>
      </b-tab>
      <b-tab title="Login">
        <Login></Login>
      </b-tab>
      <b-tab title="SignUp">
        <signup></signup>
      </b-tab>
    </b-tabs>
  </div>
</template>

<script>
import Login from './Login.vue'
import Signup from './Signup.vue'

export default {
  components: { Login, Signup }
}
</script>

