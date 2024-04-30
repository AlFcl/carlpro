# Aprendiendo Python con League of Legends


## Contenido
- [Introducción](#introducción)
- [Tipos de Variables](#tipos-de-variables)
  - [Enteros (int)](#enteros-int)
  - [Flotantes (float)](#flotantes-float)
  - [Cadenas (str)](#cadenas-str)
  - [Listas (list)](#listas-list)
  - [Diccionarios (dict)](#diccionarios-dict)
  - [Input y Print](#input-y-print)
- [Estructuras de Control](#estructuras-de-control)
  - [Condicionales](#condicionales)
  - [Bucles](#bucles)
- [Funciones](#funciones)
  - [Definición](#definición)
  - [Parámetros](#parámetros)
  - [Retorno](#retorno)
- [Clases y Objetos](#clases-y-objetos)
  - [Definición](#definición-1)
  - [Instancia](#instancia)

## Introducción
Este tutorial está diseñado para ayudarte a aprender los fundamentos de Python mientras exploras el universo de LoL. No necesitas experiencia previa en programación para seguir este curso.

## Tipos de Variables
En Python, hay varios tipos de datos básicos que son importantes para manejar información en tus programas. Aquí los ejemplos se relacionan con LoL:

### Enteros (int)
```python
nivel = 18  # Nivel máximo en LoL
```
### Flotantes (float)
```python
vida = 1000.0  # Vida de un campeón
```
### Cadenas (str)
```python
nombre = "Teemo"  # Nombre de un campeón
```
### Listas (list)
```python
campeones = ["Teemo", "Garen", "Lux"]  # Lista de campeones
```
### Diccionarios (dict)
```python

campeon = {
    "nombre": "Teemo",
    "vida": 1000.0,
    "nivel": 18
}  # Datos de un campeón
```


### input
```python
nombre = input("¿Cómo te llamas? ")
print(f"¡Hola, {nombre}!")
```

### print
```python
print("¡Hola, invocador!")
```



## Estructuras de Control

### Condicionales
```python
nivel = 18
if nivel == 18:
    print("¡Has alcanzado el nivel máximo!")
```

### Bucles
```python
campeones = ["Teemo", "Garen", "Lux"]
for campeon in campeones:
    print(campeon)
```

## Funciones

### Definición
```python
def saludar():
    print("¡Hola, invocador!")
```

### Parámetros
```python
def saludar(invocador):
    print(f"¡Hola, {invocador}!")
```

### Retorno
```python
def sumar(a, b):
    return a + b
```

## Clases y Objetos

### Definición
```python
class Campeon:
    def __init__(self, nombre, vida, nivel):
        self.nombre = nombre
        self.vida = vida
        self.nivel = nivel

    def subir_nivel(self):
        self.nivel += 1
```

### Instancia
```python

teemo = Campeon("Teemo", 1000.0, 18)
print(teemo.nombre)
print(teemo.vida)
print(teemo.nivel)
teemo.subir_nivel()
print(teemo.nivel)
``` 

