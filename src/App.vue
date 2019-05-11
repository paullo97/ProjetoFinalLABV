<template>
  <div id="app">
    <div class="title">Trabalho final - Laboratório de Desenvolvimento em Banco de Dados V</div>
    <img alt="Vue logo" src="./assets/logo.png">
    
    <p class="intro">Acesso</p>
    <input type="text" placeholder="CPF"><br>
    <input type="text" placeholder="CODIGO"><br>
    <button class="Acessar">Entrar</button>

    <p class="Cadastro">Não tem cadastro? <a href="#">Criar Cadastro</a></p>
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
  
  .intro{font-size: 2em; }
  .Cadastro{font-size: 1em; margin-left: 80%;}
  .title{font-size: 1.5em; background-color: rgba(0, 124, 128, 0.644); padding: 1%; height: auto; width: auto}
  input{ margin-top: 1em; height: 2em; width: 20%; border-radius: 5px; box-shadow: 2px 3px #333333; }

  .Acessar{margin-top: 2em; height: 2em; width: 10%; font-size: 1.5vw; background-color: rgb(12, 184, 98); color: white; border-radius: 10px; overflow: hidden;}
</style>