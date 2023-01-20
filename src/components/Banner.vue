<template>
    <div id="main-banner">
        <h1>Monte Seu Hamburguer!</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
#main-banner {
    background-image: url('/public/img/burger2.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    border-bottom: 3px solid #DCDCDC;
    padding: 10px 40px;
}
</style>