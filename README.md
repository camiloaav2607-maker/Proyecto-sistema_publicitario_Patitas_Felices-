# 🐾 Fundación Patitas Felices -- Maqueta Web (HTML + CSS)

Este proyecto es una maqueta web estática diseñada para la Fundación
**Patitas Felices**, una organización dedicada al rescate, cuidado y
reubicación responsable de animales.\
El objetivo es mostrar la presencia digital de la fundación mediante una
interfaz visualmente atractiva, accesible y completamente responsiva
utilizando **HTML y CSS puro** (sin JavaScript).

------------------------------------------------------------------------

## 📌 Tecnologías utilizadas

-   **HTML5**\
-   **CSS3 (Flexbox + Grid)**\
-   Tipografías estándar del sistema\
-   Imágenes locales (carpeta `/img`)\
-   Sin JavaScript (solo animaciones CSS)

------------------------------------------------------------------------

## 🎯 Objetivos del proyecto

-   Presentar la misión, visión y labor de la fundación.\
-   Mostrar animales disponibles para adopción.\
-   Permitir al usuario contactar a la fundación por diferentes
    motivos.\
-   Ofrecer una experiencia moderna, simple y funcional.\
-   Simular interactividad solo con **CSS puro**.

------------------------------------------------------------------------

## 🧩 Estructura del proyecto

    /
    ├── index.html
    ├── adopta.html
    ├── perfil-animal.html
    ├── contacto.html
    ├── css/
    │   ├── style.css
    │   └── (otros css opcionales)
    └── img/
        ├── banner.jpg
        ├── animales/
        ├── rescates/
        └── icons/

------------------------------------------------------------------------

## 🏠 Página principal (index.html)

Incluye:

-   Banner con slogan y llamada a la acción\
-   Carrusel de imágenes (sin JS, animado con CSS)\
-   Sección de misión y visión\
-   Botones de navegación interna (Adopta, Donaciones, Voluntariado,
    Contacto, Galeria)\
-   Galería de rescates (Grid o carrusel horizontal)\
-   Footer con créditos

------------------------------------------------------------------------

## 🐶 Animales disponibles (adopta.html)

-   Catálogo con mínimo **8 animales**\
-   Cada tarjeta contiene imagen, nombre, edad, estado, tamaño\
-   Botón para ver el **perfil del animal**\
-   Diseño responsivo con Grid

------------------------------------------------------------------------

## 📄 Perfil del animal (perfil-animal.html)

Página individual con:

-   Foto grande\
-   Características (edad, sexo, tamaño, estado)\
-   Historia / descripción\
-   Datos de salud\
-   Botón "Solicitar adopción" → lleva al formulario de contacto\


------------------------------------------------------------------------

## ✉️ Formulario de contacto (contacto.html)

Incluye:

-   Nombre\
-   Apellidos\
-   Ciudad\
-   Correo electrónico\
-   Teléfono\
-   Tipo de consulta (Adopción / Donación / Voluntariado / Información /
    Otro)\
-   Mensaje\
-   Validación visual con CSS (`.error`, `.success`,
    `:placeholder-shown`)\
-   Información de contacto directo\
-   Redes sociales

------------------------------------------------------------------------

## 🎨 Diseño y estilo

-   Paleta de colores:
    -   Fondo gris oscuro `#1e1e2f / #1e1e35`\
    -   Acentos en azul `#3b82f6`\
-   Tipografía sans-serif\
-   Uso de Flexbox y Grid\
-   100 % responsivo\
-   Animaciones suaves con `transition`\
-   Scroll suave entre secciones (`scroll-behavior: smooth;`)

------------------------------------------------------------------------

## 🧪 Requisitos cumplidos

✔ Sitio sin JavaScript\
✔ Slider con CSS\
✔ Galería responsiva\
✔ Catálogo con 8 animales\
✔ Perfil individual\
✔ Formulario completo con validación visual\
✔ Responsividad en móvil\
✔ Diseño ordenado y accesible

------------------------------------------------------------------------

## 🚀 Cómo ejecutar el proyecto

1.  Clona o descarga el repositorio\
2.  Abre **index.html** en tu navegador\
3.  Si usas VS Code, se recomienda Live Server:

```{=html}
<!-- -->
```
    Click derecho → Open with Live Server

------------------------------------------------------------------------

## 👤 Autor

Proyecto desarrollado por:\
**Camilo Andrés Albarracín Valbuena**\
Fundación Patitas Felices (Maqueta educativa -- 2025)
