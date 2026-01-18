# 🎰 Bingo 

Una aplicación web profesional diseñada para la gestión y visualización de partidas de Bingo en eventos, optimizada específicamente para su uso con **proyectores** y pantallas de gran formato.

![Licencia](https://img.shields.io/badge/License-MIT-yellow.svg)
![Version](https://img.shields.io/badge/Version-1.0-blue.svg)

## ✨ Características Principales

* **Tablero 1-90:** Visualización clara y moderna con guía visual por decenas (colores sutiles para localización rápida).
* **Interfaz Adaptativa:** Diseño inteligente que se ajusta al 100% de la pantalla sin necesidad de scroll.
* **Selector de Premios:** Banner superior para indicar claramente si se juega para Línea, 2 Líneas o Bingo.
* **Carrusel de Patrocinadores:** Sección dedicada de agradecimientos con rotación automática de imágenes cada 5 segundos.
* **Panel de Control Lateral:** * Contador de bolas sacadas.
    * Visualización gigante de la última bola.
    * Historial de las últimas 5 bolas.
* **Seguridad:** Botón de reinicio con confirmación para evitar accidentes durante el juego.

## 🛠️ Instalación y Uso

1.  Clona este repositorio o descarga el archivo `index.html`.
2.  Sube los archivos a **GitHub Pages** para tener un enlace directo.
3.  Para una experiencia óptima en el evento, abre el enlace en Chrome y presiona `F11` (Modo Pantalla Completa).

## 🖼️ Configuración de Patrocinadores (Sponsors)

Para que aparezcan los logos de las empresas o personas colaboradoras:

1.  Crea una carpeta llamada `sponsors` en la raíz del proyecto.
2.  Añade tus imágenes en formato `.jpg`.
3.  Nombra las imágenes como `1.jpg`, `2.jpg`, `3.jpg`, etc.
4.  Si añades más de 3 imágenes, actualiza la lista en el código `index.html` (línea ~200 aprox):
    ```javascript
    const sponsorImages = [
        'sponsors/1.jpg',
        'sponsors/2.jpg',
        'sponsors/3.jpg',
        'sponsors/tu_imagen.jpg'
    ];
    ```

## 🎨 Personalización Estética

El proyecto utiliza variables CSS en la parte superior para facilitar cambios de color rápidos:
* `--gold`: Color principal para resaltados y premios.
* `--bg`: Color de fondo profundo para alto contraste en proyectores.
* `--card-bg`: Color de los paneles laterales.

---

## 👨‍💻 Créditos

Diseñado y desarrollado por **Carlos Pena**.

---
*Este proyecto es de código abierto. Siéntete libre de modificarlo para tus propios eventos locales.*
