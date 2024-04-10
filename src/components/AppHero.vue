<template>
    <div class="template-main">
        <h1 class="title">Titolo Centrale</h1>
    </div>
</template>

<style scoped>
    .template-main {
        height: calc(100vh);
        width: 100%;
        background-image: url(../../public/images1.jpg);
        /* background-repeat: no-repeat; */
        background-repeat: no-repeat;
        background-size: contain;
        background-size: 100% 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
    }

    .title{
        color: #B57269;
        font-size: 100px;
        font-weight: bold;
        user-select: none ;
    }
</style>