<template>
  <div>
    <h1 style="margin-left: 40%">Registrar Producto</h1>
    <div class="row">
      <div class="col-sm-12">
        <b-form-group label="Imagen" label-for="imagen">
          <b-form-file id="Imagen" placeholder="Cargar Imagen" drop-placeholder="Cargar Imagen"/>
        </b-form-group>

        <b-form-group label="Nombre" label-for="nombre">
          <b-form-input id="Nombre" type="text" required placeholder="Nombre producto"></b-form-input>
        </b-form-group>

        <b-form-group label="Precio" label-for="precio">
          <b-form-input id="Precio" type="text" required placeholder="Precio producto"></b-form-input>
        </b-form-group>

        <b-form-group label="Cantidad" label-for="cantidad">
          <b-form-input id="Cantidad" type="number" required placeholder="Cantidad producto"></b-form-input>
        </b-form-group>

        <div style="margin-left: 45%">
          <b-button type="volver" variant="dark" href="../productos">Volver</b-button>
          <b-button type="guardar" variant="primary">Guardar</b-button>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  
};
</script>

<style>
</style>
