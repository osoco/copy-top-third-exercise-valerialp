JS 

copyTopThird(picture){
  picture.height / 3 = part;
  part * 2 = doublePart;
  picture.style.top = doublePart;
}


CSS

.container{
  width: 250px;
  position:relative;
  overflow-y: hidden;
}

.secondImage{
  position: absolute;
}


//El elemento picture tendrá la clase 'secondImage'. Por lo que para resolver el ejercicio lo primero es saber cuánto ocupa un tercio por lo que se obtiene la altura de la imagen y se divide en 3.
EL contenedor tendrá un position relative y la segunda imagen ('secondImage') un position absolute por lo que esta se ubicará desde la esquina superior izquierda. Como el objetivo es que aparezca el primer tercio en la parte inferior de la primera imagen le damos un top que corresponderá a dos partes del tamaña total de la imagen.
