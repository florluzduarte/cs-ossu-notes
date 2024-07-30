Fecha de inicio: 05/07/2024

# 🏛️ CS50p: Intro to programming with Python

## 👉️ Semana 0: Functions, Variables

Una de las cosas más útiles que obtuve de esta clase es algo que muy frecuentemente se me olvida, en especial cuando estoy enfrente de un problema que me está abrumando...   

**Siempre se puede escribir el problema en pseudocódigo y luego transformarlo a la sintaxis del lenguaje que estemos usando.**  

Esta forma de trabajar el problema primero en un lenguaje natural, anotando paso a paso lo que necesitamos resolver y luego realmente pasarlo a código es muy útil.   

La mayoría de las veces que tengo un problema para resolver por delante, suelo separar ese problema en pequeñas tareas, pero olvido que puedo empezar por estas anotaciones en pseudocódigo para implementar la solución a ese problema.  

Me pareció un consejo de esos que mejor recordar y tratar de implementar para no meterse de lleno a tirar líneas de código sin antes pensar bien lo que necesitamos resolver.   

----

Hasta el momento algo que me está faltando es un poco más de contexto sobre Python: [[por-que-python]] , cuáles son sus características destacadas, por qué debería aprenderlo. Probablemente esto sea por que el curso se ocupa de enseñar la sintaxis del lenguaje pero hubiera estado bueno ese contexto extra.  

---

**Tipos de datos disponibles en Python** 🐍

- str --> cadenas de caracteres  
- int --> números enteros (negativos y positivos)  
- float --> números decimales (negativos y positivos)  
- bool --> True or False  
- list --> conjuntos de valores ordenados (array)  
- dict --> estructura de datos que relaciona "key" con "value" (object)  

----

**Built-in functions:**

💾 Range --> permite generar una `list` con valores automáticamente. Empezando el array desde el 0.  

```python
num_list = range(3)
# [0, 1, 3]
```

💾  Len --> Permite averiguar el length de un array

```python
students = ["Hermione", "Harry", "Ron"]
students_length = len(students)
```

----

**Reserved words:**

None -->  