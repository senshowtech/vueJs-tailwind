<template>
  <div>
    <Navbar pages="Login" />
    <Login />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue"; // @ is an alias to /src
import Login from "@/components/Login.vue"; // @ is an alias to /src

export default {
  components: {
    Navbar,
    Login,
  },
};
</script>

<style>
</style>