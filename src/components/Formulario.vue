<template>
    <div class="container">
      <h2>Reserva tu Mesa</h2>
      <form class="formulario">
        <label>Nombre</label>
        <input type="text" placeholder="Tu nombre">
  
        <label>Correo Electrónico</label>
        <input type="email" placeholder="tuemail@example.com">
  
        <label>Fecha</label>
        <input type="date">
  
        <label>Número de Personas</label>
        <input type="number" min="1" placeholder="Ej. 2">
  
        <button>Reservar Ahora</button>
      </form>
    </div>
  </template>
  
  <style scoped>
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-color: #f5f5f5;
  }
  .formulario {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  input, button {
    display: block;
    width: 100%;
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  button {
    background: purple;
    color: white;
    cursor: pointer;
  }
  button:hover {
    background: darkpurple;
  }
  </style>
  