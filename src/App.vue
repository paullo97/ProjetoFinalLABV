<template>
  <div id="app">
    <div class="title">Trabalho final - Laboratório de Desenvolvimento em Banco de Dados V</div>
    <!-- 
    <p class="Cadastro">Não tem cadastro? <a href="#">Criar Cadastro</a></p> --> 
    <div class="nav">
        <router-link to="/home">Login</router-link> |
        <router-link to="/cadastro">Cadastro</router-link>
    </div>
    <router-view/>
 
  </div>
</template>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  * {overflow: hidden; text-decoration: none;}
  .intro{font-size: 2em; }
  .Cadastro{font-size: 1em; margin-left: 80%;}
  .title{font-size: 1.5em; background-color: rgba(0, 124, 128, 0.644); padding: 1%; height: auto; width: auto}
  input{ margin-top: 1em; height: 2em; width: 20%; border-radius: 5px; box-shadow: 2px 3px #333333; }

  .Acessar{margin-top: 2em; height: 2em; width: 10%; font-size: 1.5vw; background-color: rgb(12, 184, 98); color: white; border-radius: 10px; overflow: hidden;}
  .Cadastrar{margin-top: 2em; height: 2em; width: 10%; font-size: 1.5vw; background-color: rgb(12, 38, 184); color: white; border-radius: 10px; overflow: hidden;}
  .nav{font-size: 2em;  padding-top: 3%;}
</style>