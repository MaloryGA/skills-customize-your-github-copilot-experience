# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Desarrollar el clásico juego de Hangman en Python, donde el estudiante practicará manipulación de cadenas, bucles, condicionales y entrada de usuario.

## 📝 Tasks

### 🛠️	Implementar selección y visualización de palabra oculta

#### Description
Crea la lógica para seleccionar aleatoriamente una palabra de una lista y mostrarla al jugador en formato oculto (_ _ _).

#### Requirements
Completed program should:

- Seleccionar una palabra aleatoria de una lista predefinida
- Mostrar la palabra oculta usando guiones bajos por cada letra
- Permitir al usuario ver el progreso después de cada intento

**Ejemplo:**
```python
Palabra oculta: _ _ _ _ _
```

### 🛠️	Procesar intentos y determinar resultado del juego

#### Description
Implementa la lógica para aceptar intentos de letras, actualizar el estado del juego y mostrar mensajes de victoria o derrota.

#### Requirements
Completed program should:

- Permitir al usuario ingresar letras y mostrar el progreso actualizado
- Llevar el conteo de intentos incorrectos restantes
- Finalizar el juego cuando la palabra se adivine o se agoten los intentos
- Mostrar mensajes claros de victoria o derrota

**Ejemplo:**
```python
Intentos restantes: 3
Palabra oculta: h a _ _ m a n
¡Felicidades, ganaste!
```