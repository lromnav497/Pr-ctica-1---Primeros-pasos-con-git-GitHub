# Git y Git-flow

## ¿Qué es Git?
Es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente durante el desarrollo de software.

### Características principales de Git:
- **Distribuido**: Cada desarrollador tiene una copia completa del historial del proyecto.
- **Ramas**: Permite crear y gestionar ramas de manera eficiente.
- **Rendimiento**: Optimizado para manejar grandes proyectos con rapidez.
- **Integridad**: Garantiza la integridad del código y el historial de cambios.

## ¿Qué es Git-flow?
Es un modelo de ramificación para Git, propuesto por Vincent Driessen, que define un flujo de trabajo robusto para gestionar el desarrollo de software.

### Ramas principales en Git-flow:
- **master**: Contiene el código en producción.
- **develop**: Contiene el código en desarrollo.
- **feature**: Ramas para desarrollar nuevas funcionalidades.
- **release**: Ramas para preparar nuevas versiones.
- **hotfix**: Ramas para corregir errores en producción.

### Flujo de trabajo en Git-flow:
1. **Crear una nueva rama feature**: Para desarrollar una nueva funcionalidad.
2. **Merge de feature a develop**: Una vez completada la funcionalidad.
3. **Crear una nueva rama release**: Para preparar una nueva versión.
4. **Merge de release a master y develop**: Una vez que la versión está lista para producción.
5. **Crear una nueva rama hotfix**: Para corregir errores críticos en producción.
6. **Merge de hotfix a master y develop**: Una vez corregido el error.
