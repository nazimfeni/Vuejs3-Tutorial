<template>
  <h1>Home Component</h1>
  <h1>{{ email}}</h1>
  
  <h1>{{ getName() }}</h1>

</template>

<script>
export default {
  name: "HomePage",
  data(){
    return {

      email:'nazim@gmail.com',
      getName:function(){
            return "Nazim"
      }
    }
  }

}
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
