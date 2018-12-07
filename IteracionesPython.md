#Iteraciones en Python:

Se denominará iteración a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetivo de acciones indicadas a través de comandos en el lenguaje python. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques for y while. Estos bloques poseen identación para reconocer  el bloque como tal.

### Uso de la instrucción for:

La instrucción for es utilizada para acotar un bloque de sentencias que tendrán una condición a evaluar para permitir la repetición de las mismas.

**Instrucción de inicio del bloque:** Se utiliza  la línea de código "for variable  in rango_de_variable:". Los dos puntos no se deben omitir son parte de la sintáxis.

**Cuerpo del bloque:** Corresponde a un conjunto de sentencias que poseen un identado porpio del bloque.

#### Ejemplo:

• Un bloque iterativo que calcula la suma del cuadrado de los números, desde el hasta el 10  partiendo de que el valor inicial de la variable que guardará el resultado sea 0.

```
resultado = 0
for i in range(2,11):
resultado +=i*i

print("La suma dá " + str(resultado))

```


### Instrucción while:

La instrucción while es utilizada para controlar un ciclo repetivo de instrucciones, bajo un sistema de condicional. Su sintaxis es:

**Línea inicio  del bloque:** Esta línea inicia con la instrucción while y debe tener un término condicional a la par, al final del término se coloca dos puntos, como " while (condicional):".

**Cuerpo del bloque:** Son un conjunto de sentencias marcadas por una identacion que se repiten hasta que la instrucción condicional de la cabecera sea falsa.

#### Ejemplo:

• Para realizar un bloque, se utiliza la instrucción while para sumar los números enteros desde el 2 hasta el 10. Inicialmente el valor de la variable que guardará el resultado vale 0.

```
resultado = 0
i = 2
while (i<11):
resultado +=i
i +=1

print("La suma dá " + str(resultado))
```
