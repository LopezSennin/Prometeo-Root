---
title: Prometeo Root – Wargame Natas
publishDate: 2025-05-19 00:00:00
img: /Prometeo-Root/assets/labs/natas.webp
img_alt: Ancient screen flickers inside a forgotten terminal temple
description: |
  Un sendero forjado en vulnerabilidades. Este laboratorio es una reimaginación del clásico juego Natas de OverTheWire, pero ambientado en el mundo de Prometeo Root.
tags:
  - Web
  - Beginner
  - Cyberpunk
  - CTF
---

## Laboratorio Prometeo: Wargame Web

> _"Hay páginas que mienten y otras que susurran. Pero solo las que se resisten merecen ser leídas."_  
> — Prometeo Root

Bienvenido al campo de pruebas. Aquí aprenderás a ver más allá de la superficie: código fuente, cabeceras HTTP, formularios engañosos, cookies traicioneras… Cada nivel es una fractura en el velo. Atraviésala.

---
<h2> 📜 Índice de Niveles </h2>

<p> Haz clic para visualizar cualquier nivel: </p>

---

<details>
  <summary><span style="font-size:1.15em; font-weight:bold; color:#00bcd4;">🔥 Nivel 00 → Nivel 01 – El Eco  de los Dioses Olvidadizos</span></summary>

  > _"Donde los portales no se cierran, ni los guardianes vigilan. Aquí los secretos duermen al aire libre, esperando al primer aliento del aprendiz."_  

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧭 Introducción </span></summary>

  <p>En esta primera cámara del templo digital, el camino está despejado. Las puertas están abiertas de par en par, como si los constructores hubieran olvidado cerrarlas. Tu única tarea es observar.</p>

  <h5> El mensaje es claro: </h5>

  > _*Antes de aprender a burlar los muros, debes reconocer cuando no existen.*_

  <br/>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧪 Objetivo Técnico </span></summary>

  El propósito de este nivel es enseñarte a leer código fuente HTML.
  El password para acceder a *__natas1__* se encuentra directamente dentro del código fuente de la página.

  <details>
  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔍 Pista Técnica</span></summary>

  - La página muestra un mensaje:  
    _"Nothing to see here..."_  
    ¿Seguro?

  - Haz clic derecho sobre la página y selecciona Ver código fuente o presiona Ctrl + U (Windows/Linux) o Cmd + Option + U (Mac).

  - Busca comentarios, etiquetas escondidas o rutas ocultas.  
    A veces los secretos no están cifrados, solo... ignorados.
  </details>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔐 Acceso </span> </summary>

  - URL: <a href="http://natas0.natas.labs.overthewire.org" target="_blank">natas0.natas.labs.overthewire.org</a>

  - Usuario: natas0

  - Contraseña: natas0

  - Método de acceso: autenticación HTTP básica

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🗝️ Resultado Esperado </span></summary>

  Una vez encontrado el password oculto, úsalo para acceder a *__natas1__* .
  Tu viaje ha comenzado. La llama de Prometeo se enciende con tu primer descubrimiento.

</details>

---

<details>
  <summary><span style="font-size:1.15em; font-weight:bold; color:#00bcd4;">🔥 Nivel 01 → Nivel 02 – Las Migas del Arquitecto</span></summary>

  > _"En un mundo donde las sombras susurran secretos, el conocimiento es la luz que revela lo oculto."_ 
  > — Prometeo Root   

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧭 Introducción </span></summary>

  <p>Has atravesado la puerta del templo, pero esta vez los guardianes han dejado una trampa sutil: el conocimiento está al alcance, pero sólo si sabes mirar tras bambalinas.</p>
  <p>La interfaz parece simple. Un botón. Una función. Pero el verdadero acertijo está en cómo se comporta la página al interactuar con ella.</p>

  <br/>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧪 Objetivo Técnico </span></summary>

  En este nivel, te intentaran bloquear pero no temas: la curiosidad es tu mejor aliada.
  El password para acceder a *__natas2__* se encuentra tras bambalinas.

  <details>
  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔍 Pista Técnica</span></summary>

  - La página te ha bloqueado el boton derecho del ratón.  
    _"Eso no nos va a detener, solo es un obstáculo insignificante."_  

  - presiona Ctrl + shift + i (Windows/Linux) o ve a Inspeccionar elemento en las herramientas de desarrollador del navegador.

  - Busca comentarios, etiquetas escondidas o rutas ocultas.  
    A veces los secretos no están cifrados, solo... ignorados.  

  </details>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔐 Acceso </span> </summary>

  - URL: <a href="http://natas1.natas.labs.overthewire.org" target="_blank">natas1.natas.labs.overthewire.org</a>

  - Usuario: natas1

  - Contraseña: (la que descubriste en el nivel anterior)

  - Método de acceso: autenticación HTTP básica

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🗝️ Resultado Esperado </span></summary>

  Encontrarás en el código fuente una pista o contraseña oculta en un campo HTML o revelada tras una simple acción. Usa esa contraseña para avanzar a  *__natas2__* .
  
  Tu viaje continúa, y la llama de Prometeo arde más brillante con cada descubrimiento.
</details>

  ---

<details>
  <summary><span style="font-size:1.15em; font-weight:bold; color:#00bcd4;">🔥 Nivel 02 → Nivel 03 – El Cometa Invisible</span></summary>

  > "Algunas rutas no se anuncian con palabras, sino con susurros en la estructura misma. Las huellas del arquitecto aún laten en los caminos olvidados."

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧭 Introducción </span></summary>

  <p>En este umbral, no hay contraseñas, formularios, ni campos ocultos.</p>
  <p>Los guardianes han dejado pistas grabadas en las sendas de los recursos, como migas cósmicas en el firmamento de la web.</p>
  <p>El acceso no se revela por fuerza bruta ni engaño, sino por la capacidad de ver más allá del contenido visible.</p>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧪 Objetivo Técnico </span></summary>

  Este nivel te introduce en el arte de inspeccionar la estructura de los recursos web: imágenes, rutas, enlaces relativos, y cómo todo archivo puede ser una puerta.

  <details>
  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔍 Pista Técnica</span></summary>

  - La pagina nos dice que no hay nada en ella, pero debemos buscar el rastro que ha dejado.  
    _"Los detalles son las huellas del arquitecto."_  

  - Localiza el __*src*__ de alguna imagen o recurso.

  - Analiza el path relativo.

  - ¿Es posible modificar la ruta en la URL y explorar el directorio?

  - Busca archivos que puedan contener información valiosa, como __*readme.txt*__, __*users.txt*__ o directamente el archivo que contenga el próximo secreto.

  - **Donde el arquitecto dejó su firma, tú hallarás la clave.**

  </details>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔐 Acceso </span> </summary>

  - URL: <a href="http://natas2.natas.labs.overthewire.org" target="_blank">natas2.natas.labs.overthewire.org</a>
  - Usuario: natas2
  - Contraseña: (la que descubriste en el nivel anterior)
  - Método de acceso: autenticación HTTP básica

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🗝️ Resultado Esperado </span></summary

  Una vez que hayas encontrado el archivo o la ruta correcta, obtendrás el password para acceder a *__natas3__*.

  </details>

  ---

<details>
  <summary><span style="font-size:1.15em; font-weight:bold; color:#00bcd4;"> 🔥Nivel 03 → Nivel 04 - Las Leyes Prohibidas de los Autómatas</span></summary>

  >  Los arquitectos intentaron ocultar sus secretos ordenando a los autómatas que no los vieran. Pero un aprendiz de lo invisible no necesita pedir permiso para observar lo que está prohibido.

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧭 Introducción </span></summary>

  <p>Aquí aprenderás a buscar las reglas que los propios administradores dejan a los bots y motores de búsqueda.</p>
  <p>En el mundo digital, los rastreadores siguen caminos marcados por los administradores, pero tú no eres un rastreador común.</p>
  <p>En el templo digital, esas reglas están codificadas en un archivo llamado robots.txt, que indica a los rastreadores qué rutas deberían (en teoría) ignorar.</p>
  <p>Pero tú no eres un rastreador.</p>
  <p>Tú eres el fuego que ilumina lo que otros evitan.</p>

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🧪 Objetivo Técnico </span></summary>
  
  Este nivel introduce:

  - Análisis de robots.txt como herramienta de reconocimiento
  - Detección de rutas ocultas o restringidas por diseño
  - Exploración manual de directorios sugeridos

  <details>
  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔍 Pista Técnica</span></summary>

  - Visualiza el código fuente del index.
  - Localiza el mensaje oculto en los comentarios HTML.
  - El comentario sugiere que existe un robots.txt, archivo estándar donde los administradores web indican qué rutas no deben ser indexadas por los motores de búsqueda.
  - Accede manualmente a:
    - http://natas3.natas.labs.overthewire.org/robots.txt
  - Allí descubrirás algo como: 
    - User-agent: *  
    - Disallow: /private/
  - Visita el directorio indicado __*(/s3cr3t/)*__ para encontrar el archivo donde yace el próximo password.
  - **"Las puertas cerradas para los autómatas son caminos abiertos para quienes caminan fuera de sus reglas."**

  </details>
  <summary><span style="font-size:2.15em; font-weight:bold;"> 🔐 Acceso </span> </summary>
  <p>Para acceder a la siguiente fase, utiliza las credenciales obtenidas en el nivel anterior.</p>

  - URL: <a href="http://natas3.natas.labs.overthewire.org" target="_blank">natas3.natas.labs.overthewire.org</a>
  - Usuario: natas3
  - Contraseña: (la que descubriste en el nivel anterior) 
  - Método de acceso: autenticación HTTP básica

  <summary><span style="font-size:2.15em; font-weight:bold;"> 🗝️ Resultado Esperado </span></summary>
  
  Una vez que hayas encontrado el archivo o la ruta correcta, obtendrás el password para acceder a *__natas4__*.
</details>
