<template>
  <div class="bg-white h-screen">
    <Navbar pages="Home" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Navbar from "@/components/Navbar.vue"; // @ is an alias to /src

@Options({
  components: {
    Navbar,
  },
})
export default class Home extends Vue {}
</script>
