<template>
    <div id="main-banner">
        <h1>JCS Lanches</h1>
    </div>
</template>

<script>
    export default{
        name: "Banner"
    }
</script>

<style scoped>
    #main-banner{
        background-image: url('/img/burger.jpeg');
        background-position: 0 -250px;
        background-size: cover;
        width: 100%;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        }

    #main-banner h1{
        color: #fff;
        background-color:#222;
        text-align: center;
        font-size: 60px;
        padding: 20px 40px;
    }
</style>