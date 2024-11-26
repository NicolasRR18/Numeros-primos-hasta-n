# Numeros-primos-hasta-n

=============================================================

El objetivo era resolver el reto 3, el cual consistia en
en plantear un algoritmo que encontrara los numeros primos
hasta un numero, entonces razon y plantee el siguiente
código: 

============================================================

```
[variables]
n : entero
Impares: entero
k: entero
i: entero
Primo: entero
inicio
  Impares:= 2k+1
  Primo:= (2k+1)/i
  Para k en rango (0,n) hacer
    Si modulo (2k+1) > n entonces
      escribir("Ya pasamos los numeros Primos menores o iguales a n, 
      entonces estos son los numeros primos menores o iguales a n")
    sino
      escribir("Se debe seguir hasta llegar a 2k+1 > n")
  Fin Para
  Para i en rango (1,2k+1) hacer
    Si modulo (2k+1)/i son solo 1 y 2k+1 entonces
      escribir("Es un numero primo")
    sino
      escribir("Es impar pero no es primo")
Fin Para
fin

```

============================================================

  Estos fueron los pasos a elaborar:
  
>-Primero razoné un modo de hallar numeros primos, y posteriormente cree
>un diagrama de flujo (en la plataforma mermeid) con fin de poder organizar mis ideas y pasos del
>algoritmo

============================================================

![image](https://github.com/user-attachments/assets/988a1fe1-12f2-46b5-aeba-9ecd9f944fe8)

![image](https://github.com/user-attachments/assets/be359ff1-014e-4d9c-812c-2a34807443f4)

============================================================

>-Posteriormente hice mi pseudocodigo en bloc de notas

============================================================

-![image](https://github.com/user-attachments/assets/2bcb440f-ade1-43c5-b0ad-d30db53fcff0)

============================================================

>-En conclusión, puedo evidenciar que mi algoritmo va bien encaminado a la hora 
>de encontrar los numeros primos menores o iguales a n, puesto que aal hallar
>los impares menores o iguales a n, tambien estoy comprobando si son primos es la
>mejor manera, aunque es bien cierto que el numero 2 es primo, esto es lo que faltaria por
>resaltar en el copdigo con fin de que a la hora de la lista, esta tambien imprima el
>numero 2 si 2 es menor o igual a n

# NICOLAS RAMIREZ RODRIGUEZ 1000506513

