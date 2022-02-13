<template>
<div class="topo">
    <h1>Oraite Dev</h1>
    <p>Criamos e codificamos soluçoes.</p>
</div>
     
</template>

<style>
.topo h1{
    font-size: 64px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}
.topo p{
    margin-top: 10px;
    font-size: 24px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}

.topo{
    padding-top: 200px;
    padding-bottom: 400px;
    background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.671), rgb(0, 0, 0)), url('../assets/projetos.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

@media(max-width: 800px){
.topo{
    background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.671), rgb(0, 0, 0)), url('../assets/home-mobile.png');
    background-repeat: no-repeat;
    background-size: cover;
}

}
</style>