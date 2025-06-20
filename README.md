# Proyecto Inicial con Git y GitHub

Este repositorio contiene las instrucciones básicas para inicializar un proyecto con Git y subirlo a GitHub, junto con un ejemplo de generación de números aleatorios en JavaScript.

## Requisitos previos

- Tener instalado [Git](https://git-scm.com/) en tu computadora.
- Una cuenta en [GitHub](https://github.com/).

## Instrucciones para inicializar Git y GitHub

### Pasos para configurar el repositorio

1. **Crea un repositorio en GitHub**:
   - Accede a tu cuenta en GitHub y crea un nuevo repositorio.

2. **Inicializa el repositorio local** en una carpeta de tu computadora:
   ```bash
   git init
   ```

3. **Agrega el repositorio remoto de GitHub**:
   ```bash
   git remote add origin <URL_DEL_REPOSITORIO>
   ```

4. **Crea un nuevo archivo** y realiza cambios en tu proyecto.

5. **Agrega los cambios al área de preparación** (staging area):
   ```bash
   git add .
   ```

6. **Realiza un commit de los cambios**:
   ```bash
   git commit -m "Descripción de los cambios realizados"
   ```

7. **Sube los cambios a GitHub**:
   ```bash
   git push -u origin master
   ```

## Extras

### Generar números aleatorios en JavaScript

Para generar un número aleatorio entero entre 0 y un valor máximo:

```javascript
let aleatorio = Math.floor(Math.random() * max);
```

- `Math.random()`: Genera un número decimal aleatorio entre 0 (incluido) y 1 (excluido).
- `max`: Es el valor máximo que deseas obtener.
