## 🚦 Flujo de trabajo

_Copyright (c) 2025. [Sergio Ridaura](https://github.com/sergio-ridaura)._

El flujo de trabajo propuesto para el desarrollo de proyectos con esta plantilla está diseñado para brindar claridad, estructura y eficiencia, facilitando una implementación alineada con los objetivos del equipo. Esta plantilla integra buenas prácticas y metodologías reconocidas, como **GitHub Flow** y **Kanban**, lo que garantiza un proceso colaborativo, organizado y adaptable.

Utiliza este flujo como una guía flexible que puedes personalizar según las características de tu proyecto. Ajusta las etapas y los detalles conforme a las necesidades de tu equipo y los objetivos específicos del desarrollo.

### Etapas del Flujo de Trabajo

Tras iniciar el proyecto y finalizar la **Configuración inicial** (ver [DEVELOP](DEVELOP.md)), el flujo de trabajo se estructura en las siguientes etapas principales. Estas etapas se repiten de forma iterativa, normalmente en ciclos de dos semanas, tantas veces como sea necesario para alcanzar los objetivos del proyecto:

#### 1. Selección de Tareas

En esta etapa, el equipo revisa y selecciona las tareas que se abordarán a continuación. Las tareas elegidas se trasladan a la columna **Por hacer** del tablero Kanban. Es esencial que cada tarea esté claramente definida, priorizada y documentada en el [Plan de Acción](ACTION_PLAN.md), lo que asegura una comprensión compartida, facilita el seguimiento y permite una ejecución eficiente por parte de los desarrolladores.

#### 2. Desarrollo

En esta fase, los desarrolladores abordan las tareas asignadas, moviéndolas a la columna **En Proceso** del tablero Kanban. Cada tarea se desarrolla en una rama independiente del repositorio, siguiendo el modelo **GitHub Flow**, lo que permite trabajar de forma aislada y facilita la integración posterior.

**GitHub Flow** es una metodología ágil basada en la creación de ramas para cada nueva funcionalidad o corrección. Este enfoque fomenta el trabajo paralelo y minimiza los conflictos en el código principal.

En caso que no se pueda avanzar con una tarea, se puede mover a la columna **Bloqueado** del tablero Kanban. Esto permite identificar rápidamente los obstáculos y facilita la colaboración para resolverlos.

Al finalizar una tarea, se genera un **Pull Request** (PR) para solicitar la revisión del código antes de fusionarlo con la rama principal. El PR debe incluir una descripción detallada de los cambios, referencias a las tareas correspondientes y cualquier información relevante para facilitar la revisión.

Los revisores colaboran proporcionando comentarios y sugerencias constructivas. Una vez aprobado el PR, se fusiona con la rama principal, actualizando el estado del proyecto y permitiendo que el resto del equipo acceda a los cambios implementados.

Cuando se completa una tarea, se mueve a la columna **Completado** del tablero Kanban, lo que proporciona visibilidad del progreso del proyecto.

#### 3. Revisión

En esta etapa, al finalizar el ciclo de desarrollo, el equipo revisa el estado general del proyecto y evalúa el progreso alcanzado. Se analizan las tareas completadas, se identifican áreas de mejora y se recopilan aprendizajes clave. Además, se discuten posibles obstáculos encontrados y se definen los próximos pasos o ajustes necesarios para el siguiente ciclo, asegurando una mejora continua en el proceso de desarrollo.

#### 4. Despliegue

En esta fase, al concluir el ciclo de desarrollo, el equipo prepara el proyecto para su despliegue en el entorno de producción. Se revisan cuidadosamente los cambios implementados, se ejecutan pruebas finales para validar la estabilidad y el correcto funcionamiento del sistema, y se verifica que todos los requisitos estén cumplidos. Una vez superadas estas validaciones, se realiza el despliegue, actualizando la versión en producción y asegurando que los usuarios accedan a las nuevas funcionalidades y mejoras. Este proceso debe estar documentado y, preferiblemente, automatizado para minimizar errores y garantizar una entrega confiable.

### Conclusión

Este flujo de trabajo proporciona una estructura clara y eficiente para el desarrollo de proyectos, promoviendo la colaboración y la calidad del software. Al seguir estas etapas y buenas prácticas, tu equipo podrá gestionar el proyecto de manera efectiva, asegurando que se cumplan los objetivos y se entregue un producto de alta calidad. Recuerda que este flujo es flexible y puede adaptarse a las necesidades específicas de tu proyecto. ¡Buena suerte!
