---
layout: post
title: Introducción a Postman
description:
image: /assets/img/blog/post-headers/postman.jpeg
noindex: true
comments: true
author: lucio
kate: hl markdown;
categories: [postman]
tags:
  - postman
keywords:
  - development
  
lang: es
---

En esta serie de artículos paso a paso, aprenderemos sobre Postman. En esta ocasión cubriremos los siguientes temas:

- ¿Qué es Postman?
- Características
- ¿Cómo hacer una primera solicitud GET API?

## Entonces, ¿qué es Postman?

Es una plataforma para construir y usar APIs. Podemos crear mejores APIs o más rápidas con la ayuda de un repositorio de API, herramientas, inteligencia, espacio de trabajo e integraciones. Cabe destacar que está construido sobre tecnologías de código abierto.

- Repositorio de API: al usar la plataforma central, puede almacenar, catalogar y colaborar fácilmente con todo su material relacionado con API, como casos de prueba, especificaciones, documentación, etc.
- Herramientas: proporciona varios conjuntos de herramientas API para acelerar el ciclo de vida de la API, como diseño, prueba, simulación, documentación, etc.
- Inteligencia: proporciona un nivel avanzado de inteligencia e información sobre las alertas de operaciones de API, búsqueda, advertencias de seguridad, informes, etc.
- Espacio de trabajo: lo ayuda a organizar su trabajo de API y colaborar en todo el mundo. Hay tres espacios de trabajo diferentes: personal, de equipo y público.
- Integraciones: es una herramienta muy importante en el medio de desarrollo de software para ir con las prácticas de API-first. Tambien podemos integrar Postman en los repositorios de código, canalización de CI/CD, de igual manera podemos crear nuestras integraciones utilizando la API de Postman, etc.

¿Entonces, qué esperas? ve y descarga Postman, comienza a diseñar, probar y documentar la API: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)

Viene en dos versiones, aplicación de escritorio y una versión web.

## Características
Proporciona un montón de características interesantes, algunas son las siguientes:

### Solicitud (Request)

- Cree, envíe y guarde solicitudes REST, SOAP o GraphQL.
- Guardar la solicitud (request) en colecciones.
- Enviar una solicitud a través de un servidor proxy, etc.

### Respuesta (Response)

- Ver código de estado, tiempo de respuesta, encabezados y tamaño.
- Ver el cuerpo de la respuesta en una vista cruda y bonita.
- Guarde la respuesta como un ejemplo, etc.

### Variables

- Soporte integrado para variables.
- Cree y establezca variables para colecciones, entornos y globales.
- Variables dinámicas para datos ficticios, etc.

### Scripts y Postman Sandbox 

- Escriba scripts a nivel de colección, carpeta o solicitud.
- Escriba guiones previos o posteriores a la solicitud para después o antes de la solicitud.
- Utilice scripts para enviar la solicitud, etc.

### Colaboración

- Cree espacios de trabajo personales o de equipo ilimitados.
- Cree un espacio de trabajo privado (solo Enterprise).
- Puede establecer roles e invitar a miembros, etc.

### Colecciones

- Son descripciones de API ejecutables.
- Puede organizar y realizar un seguimiento de las solicitudes relacionadas.
- Puede compartir colecciones en espacios de trabajo, etc.

Puede consultar más funciones interesantes aquí: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)

### ¿Cómo hacer una primera solicitud GET API?
Espero que haya instalado alguna de las versiones de Postman en su ordenador, o sino haber abierto la versión web. A continuación lo invito a que siga los pasos para realizar su primera solicitud en Postman:

Paso 1

Abramos la aplicación Postman (usando la versión de escritorio)

![image](/assets/img/blog/tutorials/intro-postman/01.png)

Una vez que haya abierto Postman, verá el resultado como se muestra en la captura de pantalla anterior. Así es como se ve la interfaz de usuario de Postman y puede ver las diversas opciones, como Iniciar sesión, Crear cuenta, Inicio, Área de trabajo, Informes, Explorar, Colecciones, API, Entornos, etc. Estas opciones las aprenderemos en próximos artículos.

Paso 2

Haga clic en el botón del icono más (+) como se muestra en la siguiente captura de pantalla:

![image](/assets/img/blog/tutorials/intro-postman/02.png)

Se abrirá la ventana emergente de solicitud en la misma ventana como la siguiente captura de pantalla:

![image](/assets/img/blog/tutorials/intro-postman/03.png)

Paso 3

A continuación, ingrese la URL para nuestra primera solicitud GET como 'https://api.github.com/users/jsgund' y haga clic en el botón Enviar como se muestra a continuación:

![image](/assets/img/blog/tutorials/intro-postman/04.png)

Una vez que haga clic en el botón Enviar, obtendrá la respuesta como se muestra en la siguiente captura de pantalla:

![image](/assets/img/blog/tutorials/intro-postman/05.png)

En este ejemplo, estamos accediendo a GitHub para que los usuarios soliciten por ID y, al final, puede ver mi ID de inicio de sesión de GitHub como "jsgund". En la respuesta, obtendrá los detalles de la identificación de inicio de sesión de GitHub "jsgund", propiedades como nombre, identificación, imageUrl, URL de seguidores, etc.

## Conclusión
En este artículo, aprendimos sobre Postman, las funciones y cómo realizar una primera solicitud GET API usando Postman. Si tiene alguna sugerencia o consulta sobre este artículo, por favor póngase en contacto conmigo.

Estén atentos para aprender cosas nuevas sobre Postman….

 Hasta la próxima...
