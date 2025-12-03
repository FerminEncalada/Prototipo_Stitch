# 🖥️ Prototipo UI – Stitch + HTML/CSS  
## Proyecto: Sistema de Reservas de Canchas Deportivas  
### Documentación del Prototipo

---

## 📌 1. Introducción

Este documento describe el prototipo de interfaz implementado para el sistema de **reservas de canchas deportivas**, desarrollado como parte de la Práctica APE-006 de la asignatura *Desarrollo Basado en Plataformas*.

El prototipo incluye un flujo completo de usuario compuesto por **ocho pantallas**, diseñadas inicialmente en **Stitch** y posteriormente implementadas en **HTML5 + CSS3**, manteniendo:

- estructura semántica,  
- diseño responsivo básico,  
- coherencia visual,  
- legibilidad y accesibilidad inicial.

---

## 📌 2. Flujo General del Prototipo

El flujo seleccionado corresponde al proceso que realiza un usuario para **reservar una cancha deportiva**, desde el inicio hasta la confirmación final del pago.

1. **Inicio**
2. **Inicio de sesión**
3. **Inicio del usuario logueado**
4. **Selección de deporte**
5. **Listado de canchas disponibles**
6. **Detalles de cancha**
7. **Confirmación de nueva reserva**
8. **Pago y finalización de reserva**

Este flujo representa el recorrido natural que realiza un usuario dentro del sistema.

---

## 📌 3. Estructura del Repositorio

frontend/prototipos/ui-stitch/
│
├── pantallas/
│ ├── inicio.html
│ ├── iniciar-sesion.html
│ ├── inicio_logueado.html
│ ├── seleccion_deporte.html
│ ├── listado_canchas.html
│ ├── detalles_cancha.html
│ ├── confirmacion_nueva-reserva.html
│ ├── confirmacion_pago.html
│ └── modificar_reserva.html
│
├── assets/
│ ├── css/
│ │ └── estilos.css
│ └── img/
│ └── (imágenes exportadas de Stitch)
│
└── docs/
└── ui_prototipo_stitch.md ← este archivo


---

## 📌 4. Documentación de Pantallas

A continuación, se detalla cada pantalla del prototipo.

---

# 🟦 4.1 Pantalla 1 – Inicio

**Propósito:**  
Presenta la pantalla inicial del sistema, con acceso al login. Es la primera interacción del usuario con el sistema.

**Componentes principales:**
- Header con título del sistema
- Imagen principal del prototipo
- Enlace hacia la pantalla de inicio de sesión
- Footer informativo

---

# 🟦 4.2 Pantalla 2 – Inicio de Sesión

**Propósito:**  
Permitir al usuario ingresar al sistema mediante su cuenta.

**Componentes:**
- Logo o título
- Formulario de inicio de sesión (correo/usuario + contraseña)
- Botón “Ingresar”
- Opcional: enlace para recuperar contraseña

---

# 🟦 4.3 Pantalla 3 – Inicio (usuario logueado)

**Propósito:**  
Mostrar al usuario las opciones principales una vez ha iniciado sesión.

**Componentes:**
- Navegación hacia:
  - Reservar canchas
  - Mis reservas
- Imagen o tarjeta principal
- Header con bienvenida

---

# 🟦 4.4 Pantalla 4 – Selección de Deporte

**Propósito:**  
Permitir al usuario seleccionar un deporte para filtrar las canchas.

**Componentes:**
- Cuadrícula de tarjetas (grid responsivo)
- Botones o enlaces en cada tarjeta (fútbol, tenis, básquet, etc.)
- Imágenes representativas

---

# 🟦 4.5 Pantalla 5 – Listado de Canchas

**Propósito:**  
Mostrar las canchas disponibles según el deporte seleccionado.

**Componentes:**
- Lista o grid de canchas
- Imágenes de referencia
- Botón “Ver detalles”
- Información básica como ubicación, horario o disponibilidad

---

# 🟦 4.6 Pantalla 6 – Detalles de la Cancha

**Propósito:**  
Permitir visualizar información completa de la cancha y proceder a reservar.

**Componentes:**
- Imagen principal
- Descripción de la cancha
- Precio / horario disponible
- Botón “Reservar”

---

# 🟦 4.7 Pantalla 7 – Confirmación de Nueva Reserva

**Propósito:**  
Mostrar los detalles seleccionados antes del pago.

**Componentes:**
- Resumen de cancha seleccionada
- Fecha y hora
- Costo total
- Botón “Continuar al pago”

---

# 🟦 4.8 Pantalla 8 – Pago y Finalización

**Propósito:**  
Simular la fase final del proceso de reserva.

**Componentes:**
- Resumen final
- Métodos de pago (si aplica)
- Mensaje de confirmación

---

## 📌 5. Diseño y Tecnologías Utilizadas

- **HTML5**: estructura semántica completa.  
- **CSS3**: estilos globales, grid, flexbox y media queries.  
- **Stitch**: prototipado previo.  
- **VS Code + Live Server**: pruebas responsivas locales.  
- **GitHub**: versionamiento y almacenamiento del prototipo.  

---

## 📌 6. Conclusiones del Prototipo

- El flujo completo del proceso de reserva se visualiza de forma clara.  
- El prototipo sirve como base sólida para un desarrollo frontend real.  
- El uso de etiquetas semánticas mejora orden, accesibilidad y mantenibilidad.  
- La estructura del repositorio permite escalar fácilmente el proyecto.  
- La integración Stitch → HTML/CSS se cumplió en todas las pantallas.

---

## 📌 7. Evidencias

Las capturas se encuentran en:

frontend/prototipos/ui-stitch/assets/img/

