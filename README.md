# WebReel
# Pràctica Transversal: **WebReel — El teu vídeo al web**

> **Cicle:** CFGS Desenvolupament d'Aplicacions Web (DAW) **Mòduls implicats:** 0485 Programació · 0612 DWEC · 0615 Disseny d'interfícies web · 0489 Programació multimèdia i dispositius mòbils.

---

## 1. Descripció general
En mi video explico brevemente como funcionan las **interfaces** en **TypeScript**, también creo un par de **objetos** basados en la interfaz y luego mediante una **función** los añado a una **lista**. Finalmente los imprimo por pantalla en la terminal para que se vea el resultado de todo el proceso. En cuanto a la web, he usado **HTML**, **CSS** y **JavaScript** para construirla y darle funcionalidad. 

---

## 2. HTML
Tengo dos archivos **HTML**, uno se llama index y el otro about. En el primero tengo la estructura de la página de inicio, tengo links a los **js** y al **styles.css**, un header y un footer, un main en el cual guardo 4 secciones: una para el contenedor del video, otra para los botones de reproduccion, otra para los highlights del video y la última para los comentarios. En el otro HTML tengo los mismos header y footer, un contenedor con la descripción del proyecto y una sección para la API. 

---

## 3. CSS
Tengo un solo archivo CSS en el cual le doy estilo a ambos HTML, le he dado un uso bastante básico para darles un poco de forma a los botones y contenedores, también lo he usado para cambiar los colores a los elementos de la página.

---

### 4. JavaScript

Tengo 3 archivos JS, uno se llama main.js y es donde tengo creada la clase del reproductor del video con todas sus funciones, también tengo creadas las funciones de los botones de reproduccion, de los botones de los highlights, de la persistencia en el sessionStorage para que se guarden los segundos del video y al hacer refresh en la página se pueda reproducir des del minuto en el que se quedó guardado y por último la de los comentarios, para que estos se guarden en el LocalStorage. Tengo el api.js en el que hago el fetch a la api de anime y para cargar la imagen de Gojo y por último tengo el storage.js que es el que uso para exportar al main.js las funciones del reproductor de video, del reproductor de audio y del almacenamiento de los comentarios.
---

