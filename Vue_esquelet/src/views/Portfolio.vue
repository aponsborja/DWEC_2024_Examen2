<template>
  <div class="home">
    <div class="container mt-5">
      <h1>Portfolio</h1>
      <div class="row mt-4">
        <!-- Categorias -->
        <div class="row mt-4">
          <div class="col-2">
            <button type="button" class="btn btn-primary">{Categoria 1}</button>
          </div>
          <div class="col-2">
            <button type="button" class="btn btn-primary">{Categoria 2}</button>
          </div>
          <div class="col-2">
            <button type="button" class="btn btn-primary">{Categoria 3}</button>
          </div>
          <div class="col-2">
            <button type="button" class="btn btn-primary">{Categoria 4}</button>
          </div>
        </div>        
        <div class="row mt-4">
          <!-- Tarjetas -->
          <div class="col-md-3 mb-4">
            <div class="card">
              <img src="#" class="card-img-top" />
              <div class="card-body">
                <h5 class="card-title">{Título 1}</h5>
                <p class="card-text">{Fecha 1}</p>
              </div>
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="card">
              <img src="#" class="card-img-top" />
              <div class="card-body">
                <h5 class="card-title">{Título 2}</h5>
                <p class="card-text">{Fecha 2}</p>
              </div>
            </div>
          </div>          
          <!-- Fin de las tarjetas -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Portfolio",
};
</script>
