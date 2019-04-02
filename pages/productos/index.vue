<template>
  <div>
    <h1 style="margin-left: 35%">Listado de productos</h1>

    <div style="row mt-2">
      <div style="col-sm-12">
        <b-table striped hover :items="items" :fields="fields"></b-table>
      </div>
    </div>

    <div style="margin-left:42%">
      <br>
      <br>
      <b-button href="/productos/nuevo" type="button" class="btn btn-success">Nuevo producto</b-button>
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      fields: [
        "Imagen",
        "Nombre",
        "Precio",
        "Cantidad",
        "Acciones"
        /*items:
           { isActive: true, age: 40, first_name: 'Dickerson', last_name: 'Macdonald' },
          { isActive: false, age: 21, first_name: 'Larsen', last_name: 'Shaw' },
          { isActive: false, age: 89, first_name: 'Geneva', last_name: 'Wilson' },
          { isActive: true, age: 38, first_name: 'Jami', last_name: 'Carney' } */
      ]
    };
  }
};
</script>

<style>
</style>

 
