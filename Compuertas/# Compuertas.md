# Compuertas 

*  Digitales
    * Matematica (Algebra)
    * Logica (Filosofia)
  
**Con ambas se genera el algebra de bool**

## Preposiciones

* Oraciones Que pueden ser tomadas como __verdaderas(1)__  o  __falsas(0)__

* Hoy es viernes
* Hoy es martes y salio el sol
  
### Las Preposiciones pueden ser **Simples** o **Compuestas** 

* Una simple es : Hoy salio el sol 
* Las compuestas encambio tienen conectores logicos **y o** y otros mas ej: Hoy tengo clases y llueve 

### Como cada preposicion puede tomar valores de verdad , lo que se hace es armar una tabla de verdad
Oracion | Hoy Tengo clases | LLueve 
--------|------------------|-------
 0 |Falso|Falso 
 1 |Falso|Verdadero
 2 |Verdadero|Falso
 3 |Verdadero|verdadero


 ### Para saber cuantas opciones posibles puedo tener se hace una simple ecuacion 2 ^ n  (Con n la cantidad de entradas)

 ##### Si Yo los uno con una y Tendria que ocurrir ambas para que sea verdadera
 ##### Si encambio usa una o tendria que ser  una o la otra

### Compuerta AND (y)

* Para que la salida de ella sea un 1 o un verdadero tiene que ser ambas verdaderas (Las entradas)
* Tiene 2 Entradas 
* Su ecuacion es A . B = C
* 
Oracion | A | B|C 
--------|--------|----------|-------
 0 |Falso|Falso |Falso
 1 |Falso|Verdadero|Falso
 2 |Verdadero|Falso|Falso
 3 |Verdadero|verdadero|Verdadero


### Compuerta OR (o)
* En las salidas con que almenos una de las entradas sea verdadera la salida sera verdadera
* Tiene 2 entradas 
* Su ecuacion es A + B = C 

 Oracion | A | B|C 
--------|--------|----------|-------
 0 |Falso|Falso |Falso
 1 |Falso|Verdadero|Verdadero
 2 |Verdadero|Falso|Verdadero
 3 |Verdadero|verdadero|Verdadero

### Compuerta NOT (Negacion)
* Lo que hace esta compuerta es a lo que entra lo niega 
* -A = S
  
A|-A|S
--|---|---
  |F|V|V
  |V|F|F

