---
layout: post
title: Primeros pasos con Microsoft .NET MAUI
description:
  
image: /assets/img/blog/post-headers/maui/maui01.png
noindex: true
comments: true
author: lucio
kate: hl markdown;
categories: [maui]
tags:
  - maui
  - net
keywords:
  - maui
  - net
lang: es
---

La interfaz de usuario de la aplicación multiplataforma .NET (.NET Multi-platform App UI (.NET MAUI)) es la evolución del kit de herramientas de Xamarin.Forms. Teniendo en cuenta la productividad del desarrollador, MAUI simplifica la estructura del proyecto en un solo proyecto para apuntar a múltiples plataformas (Android, iOS, macOS y Windows).

En esta serie de artículos, exploraremos MAUI y aprenderemos a crear nuestra ya famosisima primera aplicación de "Hola Mundo".

A continuación brindo los temas que nos permitirán conocer más y así comenzar con .NET MAUI:

- ¿Qué es .NET MAUI, para quién es, cómo funciona?
- Ventajas de MAUI sobre otros marcos multiplataforma (frameworks)
- Instalación de requisitos previos para el desarrollo multiplataforma con MAUI
- Instalación de MAUI
- Creación de una aplicación usando .NET MAUI 

---------------------------------------------------------

# Importante -> Requerimientos Técnicos

Este artículo está dirigido principalmente a desarrolladores de .NET con cierta experiencia con Xamarin y .NET.

Para la aplicación de tareas pendientes, se requiere un entorno de desarrollo de Windows 10, ya que la compatibilidad de Visual Studio para Mac con .NET MAUI está prevista para una versión futura.

Idealmente, debería tener un dispositivo macOS con Xamarin.iOS y Xcode instalado conectado a su entorno de Windows 10. Esto se debe a que lo necesitará compilar y usar el simulador de iOS. Con esta configuración, es decir, Windows y Mac, podemos probar la aplicación de tareas en múltiples plataformas (Android, iOS, macOS y Windows).

### Nota: 

Actualmente, Visual Studio 2022 solo puede implementar aplicaciones de .NET MAUI iOS en el simulador de iOS, y no en dispositivos físicos.

En el siguiente enlace se puede encontrar el código utilizado en este artículo: GitHub

## ¿Qué es .NET MAUI, para quién es, cómo funciona?
.NET MAUI es un marco multiplataforma para crear aplicaciones nativas de escritorio y móviles con C # y XAML. Funciona como una capa de abstracción que gestiona la comunicación de código compartido con plataformas subyacentes como Android, iOS, macOS y Windows.

.NET MAUI le permite crear una interfaz de usuario nativa en cada plataforma y escribir lógica empresarial en C # que se comparte entre plataformas. Está construido sobre .NET, lo que significa que maneja tareas como la asignación de memoria, la recolección de basura y la interoperabilidad con las plataformas Android, iOS, macOS y Windows.

.NET MAUI es para desarrolladores que desean escribir aplicaciones multiplataforma usando C # desde una única base de código compartida en Visual Studio

Si ha utilizado anteriormente Xamarin.Forms para crear interfaces de usuario multiplataforma, notará muchas similitudes con .NET MAUI. De hecho, .NET MAUI es la evolución de Xamarin.Forms. Sin embargo, simplifica la estructura del proyecto en un solo proyecto para apuntar a múltiples plataformas. En Xamarin.Forms, tiene un proyecto para cada plataforma de destino y otro proyecto para una base de código compartido:

![image](/assets/img/blog/tutorials/nuevo-proyecto-blazor/newproject01.png)
