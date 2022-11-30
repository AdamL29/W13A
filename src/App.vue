<template>
  <div id="app">
    <HeadAttempt/>
    <BodyAttempt/>
    <FooterAttempt/>
  </div>
</template>

<script>
import HeadAttempt from "@/components/header.vue";
import BodyAttempt from "@/components/body.vue";
import FooterAttempt from "@/components/footer.vue";

export default {
  name: 'App',
  components: {
    HeadAttempt,
    BodyAttempt,
    FooterAttempt
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
