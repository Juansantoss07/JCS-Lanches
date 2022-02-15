<template>
  <nav>
    <Router-link to="/" id="logo_url">
    <img :src="logo" :alt="alt" id="logo"></Router-link>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/pedidos">Pedidos</RouterLink>
  </nav>
</template>

<script>
    export default{
        name: "Navbar",
        props:[
            "logo", "alt"
        ]
    }
</script>

<style scoped>
    nav{
        background-color: #222;
        border-bottom: 4px solid #111;
        padding: 15px 50px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    
    #logo{
        width: 40px;
        border-radius: 5px;
    }

    #logo_url{
        margin: auto;
        margin-left: 0;
    }

    nav a{
        color: #FCBA03;
        text-decoration: none;
        margin: 12px;
        transition: 0.5s;
    }

    nav a:hover{
        color: #fff;
    }
</style>
