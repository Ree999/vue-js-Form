<template>
  <signUpForm />
</template>

<script>
import signUpForm from './components/signUpForm.vue' //calling Signupform

export default {
  name: 'App',
  components: { signUpForm}
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
body{
  margin: 0;
  background: #eee;
}
</style>
