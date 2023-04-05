<template>
<div class="container">
  <div class="my-class">My component {{name}}</div>
    <div>
      <div class="my-class">My component part 2 {{name}}</div>
      <div class="my-class">My component part 2 {{name}}</div>
    </div>
  <div class="my-class">My component part 3 {{name}}</div>
  </div>
</template>

<script>

export default {
    props:['name'],
    name: "header"
}
</script>

<style scoped>
.my-class{
background-color:red;
margin-top: 10px;
}
.container{
  display:flex;
  flex-direction:row;
  align-items:center; 
}
</style>