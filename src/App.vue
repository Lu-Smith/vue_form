<template>
  <h1>Hello World</h1>
  <SignupForm />
</template>

<script>
import SignupForm from './components/SignupForm.vue';
export default {
  name: 'App',
  components: {
    SignupForm
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
  background: #eee;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
