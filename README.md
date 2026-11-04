# Plataforma de Gestión y Contratación de Tutorías Académicas

Sistema web interactivo diseñado para conectar estudiantes con tutores académicos, facilitando la contratación de clases particulares, la concertación de horarios y precios según la complejidad de la materia, y la gestión de recursos de estudio digitales.

## Propósito del Proyecto

El proyecto resuelve la necesidad de centralizar el proceso de aprendizaje personalizado. La plataforma permite a los usuarios registrarse e ingresar de forma segura, buscar tutores por área de conocimiento, coordinar la disponibilidad horaria, pactar tarifas según el nivel de dificultad de la asignatura y acceder a una biblioteca de libros electrónicos y material de consulta.

## Arquitectura y Tecnologías

El desarrollo del sistema se realizó con un stack enfocado en rendimiento y compatibilidad web estándar:

- Frontend: HTML5, CSS3 para el diseño responsivo y JavaScript (Vanilla) para la reactividad e interacción en el cliente.
- Backend: PHP para el procesamiento de la lógica de negocio, manejo de sesiones de usuario y solicitudes de contratación.
- Base de Datos: MySQL para el almacenamiento relacional de usuarios, credenciales, materias, solicitudes de tutoría y catálogo de libros.
- Control de Versiones: Git y GitHub.

## Módulos y Funcionalidades

### 1. Autenticación y Gestión de Usuarios (Login y Registro)
- Registro de nuevos usuarios con validación de datos en tiempo real.
- Inicio de sesión seguro (Login) con manejo de sesiones en PHP.
- Diferenciación de perfiles y roles de acceso (Estudiante y Tutor).

### 2. Perfiles de Tutores y Contratación
- Catálogo de tutores disponibles categorizados por especialidad o tipo de materia.
- Sistema de contratación directa de tutorías entre el estudiante y el tutor seleccionado.

### 3. Negociación y Coordinación de Sesiones
- Módulo para fijar y acordar horarios disponibles entre ambas partes.
- Establecimiento de tarifas y precios personalizados en función del nivel de dificultad de la asignatura.

### 4. Biblioteca Digital y Recursos
- Repositorio de libros electrónicos y material bibliográfico en formato digital para reforzar las clases.
- Clasificación de recursos educativos organizados por materia y nivel académico.

### 5. Control y Base de Datos Relacional
- Estructura relacional en MySQL para vincular usuarios registrados, credenciales, horarios acordados y material bibliográfico asignado.


## Autor

José Ángel Fernández González  
Ingeniero en Sistemas
