<template>
  <div class="footer">
    <div class="row">
   
    <div class="caja1 col-4">
      <label for="inputName" class="form-label">Nombre</label>
    <input type="name" id="inputName" class="form-control" aria-describedby="nameHelpBlock">
  <div id="nameHelpBlock" class="form-text">
  Escribe tu nombre.
</div>
<label for="inputMail" class="form-label-2">Correo electrónico</label>
    <input type="mail" id="inputMail" class="form-control" aria-describedby="mailHelpBlock">
  <div id="mailHelpBlock" class="form-text">
  Escribe tu email.
</div>
    </div>

    <div class="caja2 col-4">
      <label for="inputComments" class="form-label">Comentarios</label>
    <input type="comments" id="inputComments" class="form-control inputlargo" aria-describedby="commentsHelpBlock">
  <div id="commentsHelpBlock" class="form-text">
  Deja tus comentarios.
</div>
<button type="submit" class="btn btn-light">Enviar</button>
    </div>
   
    <div class="contacto col-4">
      <p>nat.webdeveloper@gmail.com</p>
  <p>+56 9 97830991</p>
    </div>

    </div>
</div>
      
</template>
   

<script>

import emailjs from 'emailjs-com';
export default {
    name: "Footer", 
}
</script>

<style scoped>
.footer {
  flex-shrink: 0; 
  padding: 20px;
  background-color: #FCFCE2;
  margin-top: 20px;
  box-shadow: 2px 2px 5px 0;
  /* border-radius: 10px; */
}

input {
  height: 25px;
  
}

.inputlargo {
height: 100px;
 
}

.form-label {
  font-size: 14px;
  margin-top: 0px;
}

.form-label-2 {
  font-size: 14px;
  margin-top: 10px;
}

.form-text {
  font-size: 11px;
}

button {
 background-color: #EED5EE;
 font-size: 10px;
 border-radius: 2px;
 box-shadow: 2px 2px 5px 0;
 height: 25px;
 
} 

.contacto {
  font-size: 14px;
  margin-top: 50px;
  color: gray;
}

.row {
  margin-top: 0;
}

</style>