#  CSS + JS Clock - JavaScript30 Day 2

##  Descripción del Reto
Este proyecto replica el **Reto #2 "CSS + JS Clock"** del curso [JavaScript30](https://javascript30.com/) de Wes Bos. El objetivo es construir un reloj analógico funcional utilizando únicamente HTML, CSS y JavaScript vanilla, sin frameworks ni librerías externas.

El reto demuestra cómo manipular el DOM y usar transformaciones CSS para crear animaciones fluidas de las manecillas del reloj en tiempo real.

## Demo en Vivo
**[Ver Demo](https://mateos20013.github.io/TalentMatch/)**


##  Tecnologías Utilizadas
 Tecnología ------> Uso 

**HTML5** -----> Estructura semántica del reloj 
**CSS3** -----> Estilos, transformaciones y transiciones 
**JavaScript ES6+** -----> Lógica de tiempo y manipulación del DOM 

##  Características
**Reloj Analógico:** Tres manecillas (hora, minutos, segundos) con movimiento en tiempo real
**Diseño Atractivo:** Fondo con imagen blur, borde blanco y sombras para profundidad
**Efecto de Rebote:** Transición `cubic-bezier` para un movimiento natural de las manecillas
**Responsive:** Se adapta a diferentes tamaños de pantalla

## Estructura del Proyecto
```
CSS-JS-Clock
    css
      style.css      (Estilos del reloj)
    js
      script.js      (Lógica JavaScript)
    index.html         (Estructura HTML)
    README.md          (Documentación)
```

## Instalación y Ejecución Local
1. **Clona el repositorio:**
   
   git clone https://github.com/Mateos20013/TalentMatch.git
   
2. **Navega al directorio:**
   
   cd TalentMatch
   
3. **Abre el archivo en tu navegador:**

##  Conceptos Aplicados
- Manipulación del DOM con `querySelector`
- Cálculo de ángulos para rotación (grados = (valor/total) × 360)
- CSS `transform: rotate()` y `transform-origin`
- CSS `transition` con `cubic-bezier` para animaciones
- `setInterval()` para actualización cada segundo
- Objeto `Date()` de JavaScript

##  Autor
**Mateo Sebastián Sotomayor BENAVIDES**  
Estudiante de Ingeniería Web - Séptimo Semestre  
GitHub: [@Mateos20013](https://github.com/Mateos20013)

## Licencia
Este proyecto está bajo la Licencia MIT.

---
 Desarrollado como parte del curso **JavaScript30** por Wes Bos
