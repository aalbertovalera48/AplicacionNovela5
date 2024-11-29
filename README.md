# Aplicación de Gestión de Novelas Actualizada - Alberto Valera

**Link al Repositorio:**

**Link a la Base de Datos Firebase:** 

## Objetivo

El objetivo de este ejercicio es optimizar la aplicación Android desarrollada en los Ejercicios de Feedback anteriores para mejorar su rendimiento y reducir el consumo de recursos. Los estudiantes aprenderán a utilizar herramientas de perfilado, reducir el uso de memoria, mejorar el rendimiento de la red y optimizar el uso de la batería.

## Enunciado

En este ejercicio, diseñarás y desarrollarás una aplicación Android para gestionar una biblioteca personal de novelas. La aplicación debe cumplir con los siguientes requisitos adicionales:

### 1. Optimización del Uso de la Memoria
- Reducir las fugas de memoria utilizando el **Memory Profiler** para identificar y corregir problemas de gestión de memoria.
- Implementar técnicas de optimización de memoria, como el uso eficiente de `Bitmap` y el reciclaje de vistas.

### 2. Mejora del Rendimiento de la Red
- Utilizar el **Network Profiler** para analizar y optimizar el uso de la red, minimizando el consumo de datos y el tiempo de respuesta.
- Implementar compresión de datos y técnicas de uso eficiente de la red para reducir el consumo de datos móviles.

### 3. Optimización del Uso de la Batería
- Usar **batterystats** y **Battery Historian** para identificar y resolver problemas relacionados con el consumo de batería.
- Implementar prácticas recomendadas para minimizar el uso de la batería, como reducir la frecuencia de las actualizaciones en segundo plano.

### 4. Interfaz de Usuario
- Diseñar una interfaz intuitiva y fácil de usar.
- Utilizar vistas y layouts apropiados para organizar los elementos de la interfaz de usuario, asegurando un rendimiento óptimo.

---

## Características Principales

- **Interfaz amigable:** Diseño intuitivo y moderno.
- **Sincronización en tiempo real:** Lista de novelas conectada con Firebase.
- **Gestión de favoritos:** Marcar y administrar novelas favoritas.
- **Notificaciones:** Recordatorios configurables con `AlarmManager`.
- **Optimización:** Reducción del uso de memoria, consumo de batería y mejor rendimiento de red.

---

## Funcionalidades de la Aplicación

1. **Pantalla de Lista de Novelas:**
   - Lista interactiva de novelas con navegación a detalles.
   - Agregar nuevas novelas desde un formulario.
   - Marcar novelas como favoritas.

2. **Pantalla de Detalles:**
   - Visualización detallada de novelas (título, autor, año, sinopsis).
   - Gestión de reseñas.
   - Marcar o desmarcar como favorita.

3. **Pantalla de Agregar Novela:**
   - Formulario validado para registrar novelas (título obligatorio).
   - Almacenamiento automático en Firebase.

4. **Sincronización y Notificaciones:**
   - Sincronización de datos en segundo plano.
   - Recordatorios sobre novelas favoritas usando `AlarmManager`.

5. **Optimización de Recursos:**
   - Uso de herramientas como **Memory Profiler**, **Network Profiler** y **Battery Historian** para mejorar el rendimiento general de la aplicación.

---

## Clases y Componentes

### Principales Clases

1. **MainActivity**
   - Actividad principal que gestiona la lista de novelas.
   - Métodos para CRUD de novelas y sincronización con Firebase.

2. **FavoritosActivity**
   - Actividad para visualizar y gestionar novelas favoritas.

3. **Novela**
   - Modelo de datos que incluye título, autor, sinopsis, estado favorito y reseñas.

4. **NovelaAdapter**
   - Adaptador personalizado para enlazar datos de novelas con la interfaz gráfica.

5. **SyncTask**
   - Clase `AsyncTask` para sincronización en segundo plano con Firebase.
   - 
## Estructura del Código

- **Pantallas.kt:** Gestión centralizada de pantallas y lógica de la aplicación.
- **activity_main.xml:** Diseño principal para lista de novelas.
- **item_novela.xml:** Diseño para elementos individuales en la lista.

