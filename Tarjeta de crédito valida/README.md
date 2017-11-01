Tarjeta de crédito válida

Crea una web que pida, por medio de un prompt(), el número de una tarjeta de crédito y confirme su validez según el algoritmo de Luhn. Lee este blog que explica cómo funciona el algoritmo de Luhn.

Consideraciones Específicas

Tu código debe estar compuesto por 1 función: isValidCard
El usuario no debe poder ingresar un campo vacío

#SeudoCodigo

1. Preguntar al usuario el numero de su tarjeta por medio de la variable numCard
2. Crear una funcion de nombre isValidCard dando numCard
  2.1 Ingresar a cada uno de los indices por medio de un for.
  2.2 Crear una variable de nombre j que de [i]numCard
  2.3 Ordenar a la inversa el arreglo
    2.3.1 Nombrar al array.indexOf 1, 3, 5, 7, 9, 11, 13, 15
      2.3.1.1 Multiplicar los numeros pares por 2
      2.3.1.2 Si estos >=10
        2.3.1.2.1 Sumar los numeros entre si
        2.3.1.2.2 Definir el nuevo numero
  2.4 Sumar todos los digitos (var l)
    2.4.1 Si la suma de l === 40
      2.4.1.1 return Tarjeta valida
    2.4.2 Si no es === 40
      2.4.2.1 return Tarjeta Invalida
  
