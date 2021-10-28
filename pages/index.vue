<template>
<div id="app">
    <main>
        <h1>美味ぽん酢
<span>Minecraft Server</span></h1>
    </main>
</div>

</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Kaisei+Opti:wght@700&display=swap');
html,#app{
    width:100%;
    height: 100%;
}
body,#__nuxt{
    width:100%;
    height: 100%;
    min-height: 100%;
    margin: 0;
}
@media screen and (max-width:1024px) {
    h1{
    font-size: 12vw;
    font-family: 'Kaisei Opti', serif;
    text-align: center;
    margin:0;
    line-height: 12vw;
}
h1 span{
        white-space: nowrap;
    font-size: 9vw;
    line-height: 9vw;
    }
}
@media screen and (min-width:1024px){
    h1{
    font-size: 9vw;
    font-family: 'Kaisei Opti', serif;
    text-align: center;
    margin:0;
    line-height: 9vw;
    }
    h1 span{
            white-space: nowrap;
        font-size: 7vw;
        line-height: 7vw;
    }
}
@media screen and (min-width:1400px){
    h1{
    font-size: 8rem;
    font-family: 'Kaisei Opti', serif;
    text-align: center;
    margin:0;
    line-height: 8rem;
    width:1400px
    }
    h1 span{
            white-space: nowrap;
        font-size: 6.5rem;
        line-height: 6.5rem;
    }
}

main{
    width:100%;
    height:100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
</style>