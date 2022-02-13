<template>
<div class ='formulario'>
  <h1>Faça seu pedido abaixo</h1>
  <h1>em alguns dias vamos retornar por email</h1>
  <h1></h1>
  <div class='form'>
    <form>   
    <h2>Nome completo</h2>
    <input type="text" id="lname" name="lname" >
    <h2>Email</h2>
    <input type="email" name="" id="">
    <h2>Pedido</h2>
    <div class = 'pedido'>
    <input type="text" id="pedido" name="pedido"><br><br>
    </div>
    <button> Enviar </button>
    </form></div>
</div>
</template>

<script>
export default {

}
</script>

<style>
form{
    background-color: rgb(0, 39, 70);
    width: 350px;
    position: center;
    padding-top: 10px;
    padding-bottom: 20px;
    border: 5px solid rgb(0, 3, 49);
    border-radius: 10px;
}
.formulario{
    background-image: linear-gradient(0deg, rgba(0,0,0,1) 0%, rgba(0, 11, 24, 0.829) 50%, rgba(0,0,0,1) 100%), url('../assets/topo.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    padding-top: 40px;
    padding-bottom: 100px;
}
.formulario h1{
    color: white;
    padding-bottom: 20px;
}
.formulario h2{
    color: white;
    padding-bottom: 20px;
}
.formulario input{
    width: 300px;
    height: 30px;
    margin-bottom: 10px;
}
.pedido input{
    width: 300px;
    height: 130px;
}
.formulario button{
    background-color: rgb(0, 0, 0);
    color: rgb(0, 209, 246);
    font-weight: bolder;
    font-size: 18px;
    padding: 16px;
    padding-left:80px;
    padding-right: 80px;
    border: rgba(0, 0, 0, 0.349) solid 1px;
    border-radius: 10px;
    
}
.form{
    display: flex;
    justify-content: space-around;
}
</style>