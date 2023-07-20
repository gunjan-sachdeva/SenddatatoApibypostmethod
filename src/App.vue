<template>
<h1>POST method API</h1>
<input type="text" name="email" v-model="email">
<br><br>
<input type="text" name="password" v-model="password">
<input type="button" @click="addUser()" value="Add User">

</template>

<script>


export default {
  name: 'App',
 data()
 {
  return{
    email:'',
    password:''
  }
 },
 methods:{
  addUser()
  {
    console.warn(this.email,this.password);
  }
 }
}
</script>

<style scoped>

</style>
