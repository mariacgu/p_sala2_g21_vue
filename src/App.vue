<template>
<div id="h1">
      <h1>
        <img id="logo" src="@/assets/logo.png" alt="" >
        Ecoturismo en Colombia
      </h1>
      
      </div>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Rancho&effect=shadow-multiple">
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/reserva">Reserva</router-link> 
    <router-link to="/about">About</router-link>
    <router-link to="/login">Iniciar Session</router-link>
    
    
  </div>
  <router-view/>
</template>

<script>

</script>

<style>
#app {
  font-family: 'Rancho', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:darkgreen;
  background-color: #f1efe1 ;
  
}

h1{
  text-align:center;font-family: 'Rancho', serif;
	color: #192954;
    font-size: 30px;
    text-shadow: 4px 4px 4px #aaa;
}

#logo {

  width:7rem;
  height:5rem;

}
#nav {
  padding: 30px;
  background-color: #192954 ;
}

#nav a {

   color: white;

    font-size: 18px;
    text-decoration: none;
    padding: 1rem;
    height: 1rem;
	text-align:center;font-family: 'Rancho', serif;
}

#nav a.router-link-exact-active {
  
  color: rgb(46, 238, 46);
}



.button_sesion {border-radius: 25px;}
</style>
