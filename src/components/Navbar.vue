<template>
    <div id="nav">
      <div id="logo-warren">
        <router-link to="/" id="logo-url">
          <img src="/img/logoWarren.png" id="logo">
        </router-link> 
        <a>Warren</a>
      </div>  
      <router-link to="/">Sobre</router-link> 
      <select name="submenu" id="menuInvestir">
        <option hidden selected>Investir</option>
        <option value="carteiras">Carteiras</option>
        <option value="bolsa">Bolsa</option>
        <option value="broker">Home Broker</option>
      </select>
      <!-- <router-link to="/">Investir</router-link> -->
      <router-link to="/">Aprender</router-link>
      <router-link to="/">Magazine</router-link>
      <button>Login</button>
    </div>
</template>

<script>

export default {
   name: "Navbar",
}
</script>

<style scoped>
  #nav {
    background-color: #222;
    border-bottom: 1px solid #111;
    padding: 10px 50px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }

  #logo {
    width: 40px;
    height: 40px;
  }

  #logo-warren {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  h2 {
    color: #fff;
    font-size: 16px;
  }

  #nav a {
    color: white;
    text-decoration: none;
    margin: 5px;
    transition: .5s;
  }

  #nav a:hover {
    color: rgb(199, 19, 73);
  }

  select {
    border: none;
    cursor: pointer;
    font-size: 15px;
    padding: 5px;
    width: 130px;
    background-color: #222;
    color: white;
  }

  select:hover {
    color: rgb(199, 19, 73);
  }

  button {
    padding: 5px 15px;
    border-radius: 16px;
    border: none;
    background-color: rgb(199, 19, 73);
    color: white;
    cursor: pointer;
    font-weight: 500;
  }

  button:hover{
    background-color: white;
    color: rgb(199, 19, 73)
  }
</style>
