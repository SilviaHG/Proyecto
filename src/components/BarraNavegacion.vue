<template>
  <div id="Navegacion">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        
        <a class="navbar-brand" href="/">
          <img class="rounded float-start" width="110px" src="@/assets/images/logo_veterinaria-removebg.png" alt="Logo veterinaria">
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0 ms-auto">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" :to="{name: 'inicio'}">Inicio</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" aria-current="page" :to="{name: 'veterinaria'}">Productos Veterinaria</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" aria-current="page" :to="{name: 'construccion'}">Productos Construcción</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" aria-current="page" :to="{name: 'jardineria'}">Productos Jardinería</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" aria-current="page" :to="{name: 'contactenos'}">Contáctenos</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'BarraNavegacion',
}
</script>
