<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
      #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: 100%;
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #FFF;
        text-align: center;
        font-size: 50px;
        background: transparent;
        border: 4px solid black;
        padding: 20px 40px;
        margin: 50px 10px;
    }
</style> 