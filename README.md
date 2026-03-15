# lista-de-estudiantes
# Laboratorio – Lista de Estudiantes en Python

## Descripción
Este laboratorio tiene como objetivo practicar el uso de **listas en Python** y la interacción con el usuario mediante un **menú de opciones**.

El programa permite agregar nombres de estudiantes a una lista y mostrarlos en pantalla.

---

## Objetivo
- Practicar el uso de listas en Python.
- Implementar menús con `while`.
- Identificar y corregir errores de **indentación**.

---

## Código con error

```python
estudiantes = []

while True:
print("1 Agregar")
print("2 Mostrar")

opcion = input("Seleccione: ")

if opcion == "1":
nombre = input("Nombre: ")
estudiantes.append(nombre)
