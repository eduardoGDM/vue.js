<template>
    <div id="nav">
     <router-link to="/">Home</router-link>
     <p>navbar</p>
     <router-link :to="{name: 'Registro'}"> About</router-link>   

     
    </div>
</template>
<script>

export default {
 name:"Navbar"
}
</script>


<style scoped>
#nav {
    background-color:#000;
    border-bottom: 10px solid #111;
    padding:13px 50px;
    display:flex;
    text-align: center;
    justify-content:space-between;
    color: #bbb;
    

}   
</style>


