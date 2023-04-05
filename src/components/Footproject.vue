<template>
    <div class="contacto">
    <footer>
    <p class="my-class">email upc@edu.pe {{email}}</p>
    <p class="my-class">telefono 123456789 {{telefono}}</p>
    <p class="my-class">calle principal {{direccion}}</p>
     </footer>   
    </div>
</template>
<script>
export default {
    props:['email'],
    props:['telefono'],
    props:['direccion'],
    email:"footer",
    telefono:"footer",
    direccion:"footer"
}
</script>
<style scoped>
.my-class{
margin-top: 10px
}
.contacto{
   display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin-right: 20px;
} 
</style>