<template>
  <div class="home container-fluid">
    <h1>Welcome to the Denzil-Reader</h1>
    <form>
      <input type="textarea" v-model="textBody" rows="4" cols="50" />
    </form>
    <br />
    <p>
      <b>{{textBody}}</b>
    </p>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Home",
  data() {
    return {
      textBody: "input text"
    };
  },
  components: {}
};
</script>

<style scoped>
h1 {
  color: black;
  opacity: 1 !important;
}

p {
  color: black;
  font-size: 1.5rem;
}
</style>
