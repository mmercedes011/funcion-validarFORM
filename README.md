# funcion-validarFORM

function validarFormulario() {

    */----pido los campos del formulario----*/

let nombreyapellido = prompt("Ingrese su nombre y apellido");
let correo = prompt("Ingrese su correo electronico");
let edad = prompt("Ingrese su edad");
let zonaResidencial = prompt("Ingrese la zona donde vive");
let mensaje = prompt("Escriba un mensaje");

    /*----guardo los datos que obtuve----*/

console.log(nya, correo, edad, zonaR, msj);

    */---- VALIDACION----*/

    * comparo para que no haya campos vacios *

if (nombreyapellido === "" || correo === "" || zonaResidencial === "" || mensaje === "") {

alert("Ups! Por favor, completa todos los campos.");
return false; // no deberia enviar el formulario
}else {
alert("Su consulta fue enviada correctamente! En breve nos comunicaremos con usted.");
return true; // deberia enviar el formulario
}
}

validarFormulario(); --> corro la funcion

_/----POR QUE ES UTIL?----_/

Es util para que no se envien formularios vacios y de esa manera no llenar la base de datos.

_/----COMO LO PENSE Y COMO LO VAMOS A IMPLEMENTAR EN EL PROYECTO?----_/

Lo pense como una validacion simple, aun no se como implementarlo al proyecto. Porque no se como tomar los datos el formulario que ya tenemos en la pagina. En este caso "cree" un formulario a partir de prompt's y alert's
