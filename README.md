# Mi Formación CTMA

App desarrollada con **Jetpack Compose** como parte del curso de desarrollo de aplicaciones móviles del programa **Análisis y Desarrollo de Software (SENA)**.

## Tecnologías utilizadas

- Kotlin
- Jetpack Compose
- Android Studio

---

# Definición inicial del producto

## Problema

Durante la formación en el SENA, un aprendiz debe entregar talleres y evidencias de varias competencias al mismo tiempo, muchas veces con fechas cercanas entre sí. Cuando un taller es largo o exige mucha atención, puede tomar uno o dos días completarlo, y mientras tanto otros talleres más cortos quedan relegados o se olvidan por completo. Esto genera desorden, entregas tardías y estrés innecesario, ya que no existe un lugar centralizado donde visualizar qué actividades están pendientes, cuáles ya se entregaron y cuáles se acercan a su fecha límite. Mi Formación CTMA busca resolver esto ofreciendo al aprendiz un espacio simple para registrar sus actividades, marcar su progreso y mantener control sobre sus compromisos formativos.

---

## Tipos de usuario y necesidades

| Usuario | Necesidad |
|---|---|
| **Aprendiz** | Necesita programar recordatorios para cada taller y marcar su estado (pendiente, en proceso, realizado) para no perder el control de sus entregas. |
| **Instructor** | Necesita revisar los talleres entregados por sus aprendices y dejarles retroalimentación sobre cada uno. |
| **Administrador** | Necesita gestionar los perfiles de usuarios (crear, editar o eliminar) y supervisar el estado general de la información registrada en la plataforma. |

---

## Historias de usuario

### Historia 1 — Aprendiz
Como aprendiz, quiero programar una alerta para cada taller y marcar su estado (pendiente, en proceso, realizado), para no perder el control de mis entregas y evitar dejar actividades atrasadas.

**Criterio de aceptación:** El aprendiz puede crear una alerta asociada a un taller, y puede cambiar su estado entre las tres opciones (pendiente, en proceso, realizado) en cualquier momento.

### Historia 2 — Instructor
Como instructor, quiero revisar los talleres entregados por mis aprendices y dejarles retroalimentación, para orientar su proceso de formación y señalar qué deben mejorar.

**Criterio de aceptación:** El instructor puede ver la lista de talleres entregados por un aprendiz específico y escribir un comentario de retroalimentación visible para ese aprendiz.

### Historia 3 — Administrador
Como administrador, quiero gestionar los perfiles de usuario (crear, editar o eliminar) y supervisar el estado general de la información registrada, para mantener la plataforma organizada y actualizada.

**Criterio de aceptación:** El administrador puede crear, editar y eliminar un perfil de usuario, y los cambios se reflejan de inmediato en el listado general de usuarios.

---

## Estado actual del desarrollo

Este es el primer incremento del proyecto. Por ahora la aplicación cuenta únicamente con una pantalla inicial construida en Jetpack Compose (`PantallaInicio`), sin navegación ni conexión a base de datos. Los roles y funcionalidades descritos arriba representan la visión general del producto y se irán implementando en incrementos futuros.

## Autor

**[Tu nombre completo]**
Tecnólogo en Análisis y Desarrollo de Software
SENA