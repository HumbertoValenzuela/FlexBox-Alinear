# FlexBox-Alinear
*Alinear justify-content align-items align-self

* justify-content para el contenedor. flex-end;(comienza desde la derecha). 
* Flex-start; comienza de la izquierda. Center. space-around. space-between.
* Align items para el contenedor. align items para elementos verticalmente
* flex-start flex-end center
* align-self un solo elemento. valores flex-start flex-end center stretch

```javascript
.contenedor-flex {
    /* display:inline-flex; */
    display: flex;
    border: 3px solid black;
    /*justify-content para el contenedor. flex-end;(comienza desde la derecha). Flex-start; comienza de la izquierda. Center. space-around. space-between. */
    justify-content:space-between ;
    /* Align items para el contenedor. align items para elementos verticalmente */
    /*flex-start flex-end center*/
    height: 400px;
    align-items: flex-end;
}

.elemento-flex {
    padding: 10px;
    background-color: #E53935;
    /* Alinear **/ 
}
.elemento-flex:nth-child(1) {
/* align-self un solo elemento. valores flex-start flex-end center stretch*/
align-self: flex-start;
}

```
