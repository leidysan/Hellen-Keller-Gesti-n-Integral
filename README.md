# Hellen Keller Gestión Integral

## Nombre del proyecto

**Hellen Keller Gestión Integral**

## Integrantes y roles

| Integrante | Rol |
|---|---|
| Leidy Carolina Fajardo Sanchez | Diseño UX/UI, documentación, maquetación de wireframes e implementación frontend |
| Sebastián Aguilar Guido | Diseño de wireframes |
| Juan Ignacio Castro Molina | Diseño de wireframes |
| Fiorella De Mey Rojas | Apoyo en documentación y diseño |

## Descripción del proyecto

Hellen Keller Gestión Integral es una propuesta de sistema web para el Centro Nacional de Educación Hellen Keller, orientada a centralizar y optimizar los procesos académicos y administrativos de la institución.

El sistema busca facilitar la gestión de programas educativos, usuarios, docentes, terapeutas, encargados legales y estudiantes. Además, permite representar el seguimiento de los Planes Educativos Individualizados (PEI), registrar avances, consultar observaciones y mejorar la comunicación entre los diferentes actores involucrados en el proceso educativo especializado.

La propuesta incorpora principios de accesibilidad, navegación clara, diseño de alto contraste y organización visual, con el propósito de adaptarse a las necesidades de los distintos perfiles de usuario.

## Objetivo del proyecto

Diseñar e implementar una interfaz web accesible, clara y funcional que represente los principales procesos académicos y administrativos del Centro Nacional de Educación Hellen Keller mediante pantallas desarrolladas con HTML y CSS.

## Alcance del proyecto

Durante el Avance I realizó el análisis inicial del sistema y se diseñaron los wireframes de las principales funcionalidades.

En el Avance II se desarrolla la segunda iteración del proyecto mediante la implementación frontend de las pantallas definidas previamente. Esta implementación utiliza HTML semántico y CSS moderno para representar visualmente las funcionalidades del sistema y permitir la navegación simulada entre las diferentes páginas.

El proyecto contempla funcionalidades para distintos perfiles de usuario:

- Administrador.
- Docente o terapeuta.
- Estudiante.

La implementación actual corresponde a una maqueta funcional frontend. Por esta razón, los formularios, indicadores y registros muestran información simulada y todavía no se encuentran conectados a una base de datos.

## Funcionalidades implementadas

1. Inicio de sesión.
2. Recuperación de contraseña.
3. Dashboard del administrador.
4. Gestión de programas educativos.
5. Gestión de usuarios.
6. Dashboard del docente o terapeuta.
7. Mi Progreso Diario del estudiante.

## Tipos de usuario

### Administrador

Puede visualizar información general del sistema y acceder a la gestión de usuarios y programas educativos.

### Docente o terapeuta

Puede consultar estudiantes asignados, avances, actividades, observaciones y Planes Educativos Individualizados.

### Estudiante

Puede consultar su progreso diario, actividades, asistencia, observaciones y seguimiento educativo.

## Tecnologías utilizadas

- HTML5.
- CSS3.
- Flexbox.
- CSS Grid.
- Diseño responsive.
- Git.
- GitHub.

## Características de accesibilidad

El diseño incorpora elementos básicos de accesibilidad, entre ellos:

- Colores con contraste visible.
- Etiquetas `label` relacionadas con los campos de formulario.
- Texto alternativo en las imágenes.
- Estados de foco visibles en botones, enlaces y campos.
- Navegación clara y consistente.
- Botón de asistencia para escuchar instrucciones.
- Uso de etiquetas semánticas de HTML.
- Adaptación de al menos una página para dispositivos móviles.

## Estructura del repositorio

```text
Hellen-Keller-Gestion-Integral/
│
├── README.md
│
├── docs/
│   └── Hellen Keller Gestión Integral.pdf
│
├── src/
│   ├── index.html
│   ├── recuperar-contrasena.html
│   ├── administrador-dashboard.html
│   ├── gestion-programas.html
│   ├── gestion-usuarios.html
│   ├── docente-dashboard.html
│   └── estudiante-progreso.html
│
└── assets/
    ├── css/
    │   └── styles.css
    │
    └── img/
        └── recursos gráficos del proyecto

