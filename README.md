# Actividad 1
# Juego Paint

> Este proyecto es una copia de Paint en Python utilizando las librerías `turtle` y `freegames`. Permite al usuario seleccionar diferentes tipos de formas geométricas y colores de trazo mediante el teclado para dibujar en una ventana interactiva mediante clics del raton.
> Versión:2

## Funcionalidades Base
- **Puntos de referencia (Clics):** Un primer clic marca el punto de inicio (`start`) y un segundo clic en otra parte del lienzo ejecuta el trazo de la figura seleccionada.
- **Formas geométricas disponibles:**
  - Línea (`l`)
  - Cuadrado (`s`)
  - Círculo (`c`)
- **Paleta de colores base:**
  - Negro (`K`)
  - Blanco (`W`)
  - Verde (`G`)
  - Azul (`B`)
  - Rojo (`R`)
- **Acciones adicionales:**
  - Deshacer trazo (`u`)

## Funcionalidades agregadas
- Se ampliaron las herramientas de dibujo agregando soporte para trazar **rectángulos**. Se puede usar presionando la tecla r.
- Se ampliaron las herramientas de dibujo agregando la opción para trazar **Triángulos**. Se puede usar presionando la tecla t.
## Cambios en el código
- Se implementó la función que calcula el ancho y el alto a partir de dos clics. Asignado a la tecla **`r`**.
- Se completó la funció del triángulo que calcula la distancia euclidiana entre dos clics para trazar los lados del triángulo. Asignado a la tecla **`t`**
## Requisitos e Instalación
1. Asegurarse de tener Python 3 instalado.
2. Instalar la librería requerida:
   ```bash
   pip install freegames
