<template>
<div class="principal">
 <div class="cuadro">
   <h1>Lista del Compras</h1>
 </div>
    <div class="lista">
     <div class="cuadro">
       <div class="celda">
        <input type="checkbox" class="checkbox">
        <label>Huevo</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Leche</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Pan</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Jamón</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Tortillas</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Queso</label>
     </div>
    </div>
    <div class="cuadro">
     <div class="celda">
      <input type="checkbox" class="checkbox">
      <label>Plátano</label>
     </div>
    </div>
    <div class="boton">
      <button class="boton-guardar">Guardar Lista</button>
    </div>
  </div>
</div> 
</template>

<style scoped>
 .principal, .boton{
   padding: 20px;
   background-color: #292828;
   border-radius: 10px;
 }
   .cuadro{
   background-color: #000000;
   padding: 10px;
   border-radius: 10px;
   margin-bottom: 10px;
   max-width: 100%;
 }

    /* Estilo para la lista */
  .lista {
    display: grid;
    grid-template-columns: auto;
    gap: 10px;
    height: 100%;
    padding: 30px;
    background-color: rgb(51, 51, 51);
    border-radius: 10px;
  
  }
  .celda {
    display: flex;
    align-items: center;
    gap: 10px;
  }

    /* Estilo para el checkbox */
  .checkbox {
      margin: 10px 20px 10px 20px/* Alinear el checkbox a la derecha */
  }

  .boton {
    display: flex;
    justify-content: flex-end; /* Coloca los elementos al final del contenedor */
    margin-top: 200px;
  }

/* Estilo para el botón */
  .boton-guardar {
   padding: 10px 20px; /* Espaciado interno del botón */
   background-color: #4e4c4c; /* Color de fondo del botón */
   color: #ffffff; /* Color del texto del botón */
   border: none; /* Eliminar el borde del botón */
   border-radius: 5px; /* Borde redondeado del botón */
   cursor: pointer; /* Cambiar el cursor al pasar sobre el botón */
   font-family: Arial, Helvetica, sans-serif;
   width: 20vh;
  }
</style>


