# Ejercicios - Semana 03 - Infraestructuras Paralelas

- Nombre: Edinson Orlando Dorado Dorado
- Código: 1941966-3743
- Correo electrónico: edinson.dorado@correounivalle.edu.co

---

# Ejercicio 01

En este primer ejercicio vamos a usar la herramienta Valgrind para valorar que tantos accesos se hacen a la memoria cache cuando se ejecuta un programa.
Que evidencia:
- Por filas: acceso secuencial, aprovecha la localidad espacial y la cache.
- Por columnas: salto de memoria grande, mas fallos de cache y menor rendimiento.

# Ejercicio 02

Ejercicio que muestra la diferencia entre definir variables que usan la memoria stack o la memoria heap. Se enseña que la memoeria stack tiene un límite pequeño de almacenamiento (8192kb) mientras el heap es mucho mayor (hasta llenar la RAM).

# Ejercicio 03

Ejercicio que muestra que es más rápido pasar un argumento de una función usando punteros (referencia) que usando una copia (valor) ya que en el primer caso solo se copia la dirección de memoria (8 bytes) y en la otra crea una copia completa de la estructura cada vez que se llama.
