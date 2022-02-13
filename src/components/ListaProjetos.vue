<template>
<div class = "container"> 
    <div class="card">
        <img src="../assets/gifhugo.gif" alt="Denim Jeans" width= "300px" height="220px">
        <h1>Portifolio - Victorhugofny</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <a href="https://victorhugofny.vercel.app/" target="_blank"><button>SITE</button> </a>
                <a href="https://github.com/VictorHugofny/Portifolio-Vue.js" target="_blank"><button>REPOSITORIO</button></a>
            </div> 
    </div>

    <div class="card">
        <img src="../assets/luisgif.gif" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Portifolio - Luis Henrique</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <a href="https://nan-nan-sempai.github.io/pt/" target="_blank"><button>SITE</button> </a>
                <a href="https://github.com/NaN-NaN-sempai/NaN-NaN-sempai.github.io" target="_blank"><button>REPOSITORIO</button></a>
            </div>
    </div>

    <div class="card">
        <img src="../assets/gifmarcos.gif" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Portifolio - Marcos Santos</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <a href="https://github.com/Marckhos" target="_blank"><button>SITE</button> </a>
                <a href="https://github.com/Marckhos" target="_blank"><button>REPOSITORIO</button></a>
            </div>
    </div>

    <div class="card">
        <img src="../assets/douglas.gif" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Portifolio - Douglas Silva</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <a href="https://github.com/douglassantos45" target="_blank"><button>SITE</button> </a>
                <a href="https://github.com/douglassantos45" target="_blank"><button>REPOSITORIO</button></a>
            </div>
    </div>

    <div class="card">
        <img src="../assets/dark.png" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Dark_Pygmy - Game</h1>
        <p>Jogo 3d em desenvolvimento</p>
            <div class='button'>
                <a href="https://github.com/NaN-NaN-sempai/Dark_Pygmy" target="_blank"><button>SITE</button> </a>
                <a href="https://github.com/NaN-NaN-sempai/Dark_Pygmy" target="_blank"><button>REPOSITORIO</button></a>
            </div>
    </div>
</div> 

</template>

<style>
.container{
    margin-top: 100px;
    margin-bottom: 100px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
}
.container > div {
  margin-left: 10px;
  margin-right: 10px;
  margin-bottom: 10px;
  flex: 10 10 30%;
  text-align: center;
  border: rgb(1, 139, 163) 3px solid;
  border-radius: 10px;
}
.container h1,p{
    color: black;
}
.card {
  border: rgb(0, 195, 255) 3px solid;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
  background-color: rgb(2, 0, 0);
}
.card h1{
    color:white;
    padding-bottom: 20px;
}
.card p{
    color:white;
    padding-bottom: 20px;
}
.price {
  color: grey;
  font-size: 22px;
}

.card button {
  margin-top: 10px;
  outline: 0;
  padding: 12px;
  color: white;
  background-color: rgb(29, 29, 29);
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
  border: 2px solid rgba(0, 0, 0, 0.712);
}
.card a{
    width: 100%;
}

.card button:hover {
  opacity: 0.7;
}

.button{
display: flex;
}
</style>