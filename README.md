# EcoTrack

EcoTrack es un sistema de gestión ambiental desarrollado en Java que permite registrar, organizar y monitorear residuos con el objetivo de optimizar su recolección y reciclaje.

El proyecto está diseñado bajo una arquitectura MVC (Modelo–Vista–Controlador) y hace uso de estructuras de datos implementadas manualmente para gestionar la información de manera eficiente.

---

## Objetivo

Desarrollar una aplicación que facilite la administración de residuos, permitiendo su clasificación, priorización y análisis, apoyando así la toma de decisiones en procesos de reciclaje y gestión ambiental.

---

## Arquitectura

El sistema sigue el patrón MVC:

- **Modelo**: Gestión de datos y lógica de negocio  
- **Vista**: Interfaz gráfica desarrollada con Java Swing  
- **Controlador**: Manejo de eventos e interacción entre modelo y vista  

---

## Estructuras de datos implementadas

El sistema utiliza estructuras de datos desarrolladas desde cero (sin librerías externas):

- **Lista doblemente enlazada circular**  
  Almacenamiento y navegación bidireccional de residuos

- **Pila (LIFO)**  
  Procesamiento de residuos en el centro de reciclaje

- **Cola de prioridad (Heap)**  
  Gestión de rutas de recolección según nivel de urgencia

- **Árbol Binario de Búsqueda (BST)**  
  Organización jerárquica de residuos por prioridad y visualización estructurada

---

## Funcionalidades principales

- Registro y gestión de residuos  
- Clasificación por tipo y zona  
- Priorización para recolección  
- Navegación bidireccional de datos  
- Generación de estadísticas  
- Creación de reportes  
- Visualización jerárquica de información  
- Interfaz gráfica interactiva  

---

## Validaciones

El sistema implementa validaciones de datos mediante expresiones regulares, evitando el uso de bloques `try/catch` para el control de entradas inválidas.

---

## Persistencia

Los datos se almacenan mediante **serialización**, permitiendo guardar y recuperar el estado del sistema.

---

## Tecnologías utilizadas

- Java  
- Java Swing  
- Programación orientada a objetos (OOP)  
- Estructuras de datos personalizadas  

---

## Resultados

EcoTrack permite gestionar residuos de manera estructurada, integrando múltiples estructuras de datos para optimizar procesos de clasificación, priorización y análisis, ofreciendo una herramienta funcional para la gestión ambiental.

---

## Autor

Domenica Bolaños
Hillary Merino
Nicole Guevara
