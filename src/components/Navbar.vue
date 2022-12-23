<template>
    <div>
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-light">
  <div class="container-fluid">
    <router-link class="navbar-brand" to="/">
            <img class="img-fluid" src="../../public/Img/logo.png" alt=""/>
        </router-link>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav me-auto mb-2 mb-md-0">
        <li class="nav-item">
            <router-link class="nav-link active text-black" to="/">Home</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link active text-black" to="quem-somos">Quem somos</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="negocios">Negocios</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="escritorios">Escritorios</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="noticias">Noticias</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="contato">Contato</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="area-restrita">Area Restritas</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default{
    name:"Navbar"
}
</script>

<style scoped>
img{
    width: 40px;
}
</style>