<template>
  <div class="Login">
      <h1>Placement Portal</h1>
    <nav>
      <router-link to="/">Login </router-link> |
      <router-link to="/Register">Register</router-link>
    </nav>

    <img alt="Vue logo" src="../assets/Placement_Logo.jpg" />
    <Login msg="Placement Portal" />
  </div>
  
</template>

<script>
// @ is an alias to /src
import Login from "@/components/Login.vue";

export default {
  name: "LoginView",
  components: {
    Login,
  },
};
</script>
