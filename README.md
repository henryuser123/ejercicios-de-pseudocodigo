# ejercicios-de-pseudocodigo
# ejercicio 1 regar planta


console.log("elige una planta");

function regarPlanta(paso1) {
if (paso1 === 'p1') {
    console.log('ok, seleccionaste la planta *1.');
} else if (paso1 === 'p2') {
    console.log('ok, seleccionaste la planta *2.');
} else if (paso1 === 'p3') {
    console.log("ok, seleccionaste la planta *3.");
} else {
    console.log('selecciona una de las tres plantas.');
 }
}

function estaEntre(elemento, num1, num2) {
    return elemento >= num1 && elemento <= num2;
  }
  function regarPlantasCon(aguaEnMls) {
    let plantaElegida = prompt("Elige tu planta: p1, p2 o p3");
    if (plantaElegida === "p1") {
      if (estaEntre(aguaEnMls, 400, 500)) {
        console.log("Regaste la primer planta exitosamente.");
      }
    } else if (plantaElegida === "p2") {
      if (estaEntre(aguaEnMls, 40, 50)) {
        console.log("Regaste la segunda planta exitosamente.");
      }
    } else if (plantaElegida === "p3") {
      if (estaEntre(aguaEnMls, 80, 100)) {
        console.log("Regaste la tercer planta exitosamente.");
      }
    } else {
      console.log("No existe esa planta.");
    }
  }


# ejercicio 2 hacer un rembolso


  console.log('producto a devolver');

function rembolso(paso1) {
    if(paso1 === 'bolso') {
        console.log('ok');    
    } else {
        console.log(error);
        }
}

console.log('motivo del rembolso');

function rembolso(paso2) {
    if(paso2 === 'insatisfaccion') {
        console.log('ok');
    }
    else {
        console.log('ok');
    }
}

console.log('subir foto del recibo');

function rembolso(paso3) {
    if (paso3 === 'foto') {
        console.log('ok');
    } else {
        console.log ('error debe insertar una foto');
        }
}

console.log('como quiere recibir el rembolso?');

function rembolso(paso4) {
    if (paso4 === 'transferencia bancaria') {
        console.log('ok');
    } else if (paso4 === 'bono de regalo') {
        console.log('ok');
    } else {
        console.log ('elige una de las opciones dadas');
    }
}


console.log('dame el nuero de cuenta'); 

function rembolso(paso5) {
    if (paso5 === num > 9 && num < 11) {
        console.log('numero de cuenta aceptado');
    } else {
        console.log('error');
    }
}

console.log('digita tu clave');

function rembolso(paso6) {
    if (paso6 === num > 3 && num < 5) {
        console.log('correcto');
    } else console.log('error');
       
    }
