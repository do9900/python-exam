**Prueba de ingreso OpenLab - Grupo de Freelancers y asesorías - Django**

Estimados postulantes, el siguiente examen tiene como objetivo medir sus siguientes capacidades respecto a los requerimientos del grupo de Freelancers y asesorías de OpenLab.

Se evaluará: detalle de respuestas, capacidad, rol que desempeñan (hay espacio por cada rol), manejo de funciones, framework que usen. Deberán crear un FORK de este repositorio y resolver en el readme.me las preguntas así como linkear las resoluciones a los problemas de programación por este medio

1. **Responda las siguientes preguntas sobre las siguientes tecnologías: Docker, git, postman.**

- ¿Sabes que es?
- ¿Sabes para qué sirve?
- ¿Sabes cómo se usa?

1. **Responda las siguientes preguntas**

- ¿Tienes experiencia en hackatones, concursos, freelancer, laboral?
- ¿Cuéntanos sobre tu experiencia?
- ¿Qué rubro del desarrollar software te gustaría desempeñar?
  - QA
  - Desarrollo
  - Product Owner
- ¿Tienes ideas de apps o algo propio que quieras desarrollar? (ya sea como startup o libre para la comunidad)

**Resuelva las siguientes preguntas en un repositorio aparte y linkealas en tu readme.md**
- Problema 1 - Python: Para los siguientes arreglos
    1. [1,1,1,0,2,1,0,0,2,0,1,0]
    2. [1,1,1,0,2,1,0,0,2,0,0,0,1]
    3. [0,2,2,2,0,0,0,1,2,1,1,0,0,0]
    4. [3,3,3,3,3,3,3,1,0,0,0,1]

Cada arreglo representa una parcela, que tiene en cada posición una regadera. Dicha regadera tiene un valor que representa su alcance, por ejemplo en la parcela: [0,0,0,1] la regadera de la posición &quot;4&quot; puede regar 1 espacio más aparte de su misma ubicación ![](RackMultipart20201004-4-d5kd3z_html_2d8791c86d907d57.png) .

Nota:

- Cada valor &quot;X&quot; indica que una regadera puede regar una distancia &quot;X&quot; hacia ambas direcciones (Derecha e izquierda) como indica la figura.
- El cero indica que solo se riega así misma.

![](RackMultipart20201004-4-d5kd3z_html_df302043e43ab3e.png)

El objetivo de este problema es crear un algoritmo que me indique por cada arreglo presentado, la cantidad mínima de regaderas que se necesita prender para regar toda la parcela.

Si tienen una duda sobre este problema, pueden comunicarse con Edwin Deza al 987645213 y él resolverá sus dudas.

## Problema 2 - Django:

Hacer un proyecto Django con las siguientes características

- Ruteo:
  - /
    - Debe tener un texto que de la hora del sistema en el siguiente formato: DD-MM-AA - Hora - Segundos
  - /Nosotros
    - lorem ipsum
  - /Servicios
    - 4 Servicios renderizados de manera dinámica
      - Servicio:
        - Nombre
        - Descripción
        - Imagen.
- Ruteo API:
  - /usuarios - GET
    - Listado de 5 usuarios
      - Usuario:
        - Nombres
        - Apellido paterno
        - Apellido materno
        - Edad
  - /usuarios/${id} - GET
  - /crear-usuarios - POST
  - /editar-usuarios/${id} - PUT
  - /borrar-usuarios/${id} - DELETE
- Debe tener un menú con las 4 opciones de las rutas
- Se debe usar una BD SQLite