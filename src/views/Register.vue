<template>
  <div>
    <Navbar pages="Register" />
    <Register />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue"; // @ is an alias to /src
import Register from "@/components/Register.vue"; // @ is an alias to /src

export default {
  components: {
    Navbar,
    Register,
  },
};
</script>

<style>
</style>