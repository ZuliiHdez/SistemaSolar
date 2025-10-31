# SistemaSolar

## Introducción
Este proyecto representa una **simulación interactiva en 3D del Sistema Solar** desarrollada con **Three.js**, mostrando las órbitas, rotaciones y características visuales de los planetas y del Sol de forma realista.

El sistema incluye una **estrella principal (el Sol)**, los **ocho planetas** con sus respectivas texturas, y una **luna orbitando la Tierra**. Además, se han añadido un **cinturón de asteroides** y un **fondo estelar panorámico**.

Para lograr una experiencia fluida, se recomienda ejecutar el proyecto en un **navegador con soporte WebGL** y una **GPU moderna**, ya que las texturas utilizadas son de alta resolución.

---

## 🚀 Modos de Visualización

### 🔭 Vista General (General View)
En esta vista se ofrece una perspectiva global del Sistema Solar.  
Los controles se basan en **OrbitControls**, permitiendo rotar, acercar o alejar la cámara con el ratón.

**Controles:**
- 🖱️ **Botón izquierdo:** Rotar vista  
- 🖱️ **Rueda:** Zoom  
- 🖱️ **Botón derecho:** Desplazar cámara  


![Adobe Express - Vision General (2)](https://github.com/user-attachments/assets/697983bb-2bcd-4e52-b180-3af34a964cef)


### 🛰️ Modo Exploración (Exploration Mode)
Este modo permite pilotar una **nave espacial** libremente por el sistema, pudiendo acercarse a los planetas o alejarse a velocidades superiores a la luz.  
El movimiento es completamente libre e independiente del ratón.

**Controles:**
- **W / A / S / D:** Mover la nave  
- **Espacio:** Ascender  
- **Shift:** Descender  
- **V:** Alternar entre vista general y modo explorador  

El modo utiliza un sistema de **FlyControls personalizado**, simulando la inercia y el control suave de una nave espacial.


![Adobe Express - Vision Exploracion](https://github.com/user-attachments/assets/28eb083d-12c9-4735-8d51-40e4f4857ec5)


---

## ☀️ Planetas y Movimiento Orbital
Cada planeta cuenta con:
- Texturas de alta resolución (nubes, especular, atmósfera).  
- Velocidad de rotación y traslación **aproximadamente realista**.  
- Etiquetas flotantes que siempre miran a la cámara.  
- Escalas relativas ajustadas para ofrecer una experiencia visual coherente.  

El **cinturón de asteroides exterior** se ubica entre Marte y Júpiter, separado correctamente para reflejar su posición real.  
La **Luna** orbita la Tierra con una velocidad y tamaño proporcionados.

---

## 💡 Iluminación
El sistema utiliza:
- Una **luz puntual** en el centro (el Sol), que ilumina los planetas.  
- Una **luz ambiental** suave para evitar sombras excesivas.  

Gracias a este equilibrio se consigue un realismo visual atractivo, manteniendo el rendimiento en tiempo real.

---

## 🧭 Interfaz y HUD
El proyecto incluye un **HUD integrado** que muestra los controles directamente en pantalla, evitando la necesidad de consultar documentación externa.

<img width="451" height="275" alt="image" src="https://github.com/user-attachments/assets/7a093236-d218-4b79-ba66-8bf897141793" />

