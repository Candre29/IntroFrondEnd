# Requerimientos

**Es necesario tener en claro la finalidad del proyecto, por eso utilizaremos  la plantilla proporcionada por Microsoft para llenar los requerimientos del programa.**

### Links de ayuda

[https://www.youtube.com/watch?v=evi2mhhYGws](https://www.youtube.com/watch?v=evi2mhhYGws)

[https://github.com/LaunchX-InnovaccionVirtual/FrontEnd-Mision/discussions/70](https://github.com/LaunchX-InnovaccionVirtual/FrontEnd-Mision/discussions/70)

Los requerimientos básicamente son los primeros pasos para definir cuál es el problema que se quiere resolver, describir quien va a trabajar en ello, la duración, lo que se consideraría como un resultado satisfactorio, etc.

Para definirlo tienes que preguntar (ask) al cliente que es lo que quiere ¿Qué quieres que tu app haga?¿los usuarios se pueden registrar?¿qué datos tomas de cada persona? etc

- Diagrama de flujo
    
    [Flowchart_Abogabot.png](https://drive.google.com/file/d/1HEJN8xWKIwwpkqYmWevrzADjhE-Xx1Tg/view?usp=drivesdk)
    
- Organigrama
    
    [Gantt chart.pdf](https://drive.google.com/file/d/1uQQRMCBTcHf-I1xABlMSawp0IohAFeO4/view?usp=drivesdk)
    

**Caso Abogagot**

- Objetivos
    - Automatizar las demandas de sus clientes, esto lo harán a través del llenado de un formulario.
    - Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción
    - Para dar seguimiento a su demanda, el cliente crea una cuenta den la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal
    - El administrador del sitio recibe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legan en formato word para empezar el proceso.
    - El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos
    - El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso
    - Al usuario le llegan correos de notificación para saber el avance de su proceso
    - La página debe de ser responsive para poderla ver desde el celular
    - La preferencia de colores del clientes es azul marino y blanco, pro acepta propuestasll the procces

## Historia de usuario

Historias de usuario pequeñas

INVEST—> independiente, negociar, valiosa, estimar, small, testeable 

******Conversación******

Poner a las personas en primer lugar, las historias de usuarios ponen a los usuarios finales reales en el centro de la conversación. Lenguaje no técnico. Después de leer una historia de usuario, el equipo sabe por qué está compilando lo que está compilando y qué valor crea.

- Como **<Usuario>**
- Quiero **<algún objetivo>**
- Para que **<motivo>**

### Historia de usuario epicas

En general es una historia de usuario demasiado grande para que un equipo ágil la complete en una iteración. Se divide en varias historias de usuario más pequeñas antes de que se trabaje en ella.

El detalle se puede agregar a las historias de usuario de dos maneras:

- Al dividir una historia de usuario en historias de usuarios múltiples y más pequeñas
- Al agregar **“Criterios de Aceptación”**—> prueba de alto nivel que será cierta despues de que se complete la historia del usuario ágil: Debe tener un **evento, contexto y respuesta. Nos ayudan a definir mejor el alcanze**

[https://www.youtube.com/watch?v=pELieft5ziA](https://www.youtube.com/watch?v=pELieft5ziA)

**Es responsabilidad del Prodcut Owner asegurarse de que exista una Produck Backlog actualizado y riorizado.**

### Cosas a tomar en cuenta

- Definición de “Listo”
- Describe tareas o subtareas
- Perfiles de usuario
- Pasos ordenados
- Escucha el feedback
- Tiempo

## Diagramas UML

Queremos describir las diferentes cosas que están en nuestro sistema y utilizamos  **Clases** para esto

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0c7a9acd-4887-4fc5-868a-dbfa54c14c33/Untitled.png)

Identificar una instancia especifica. ATRIBUTO—> Un dato importante que contiene valores que describen cada instancia de esa clase

MÉTODOS—> Permiten especificar cualquier característica de comportmeinto de una clase

VISIBILIDAD—>Define la accesibilidad para ese atributo o método

- - privado
- + público (cualquier otra clase puede acceder)
- # protegido
- paquete

**RELACIONES** entre clases

ABSTRACCIÓN—> nombre en cursiva

- herencia —>
- Asociación—
- agregación —-<> (diamante abierto)—> una parte puede existir fuera del todo
- composición—> un objeto derivado no puede existir sin su objeto principal

MULTIPLICIDAD—> reestricciones númericas

0..1 cero a uno (opcional)

n (cantidad específica)

0..* cero a muchos

1..* uno a muchos

m..n rango específico

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fed15d34-f85c-4607-9a5f-5faf7e9835b4/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32075bf2-e0d8-4803-8bbb-93c3d90ade9a/Untitled.png)

[https://www.youtube.com/watch?v=Z0yLerU0g-Q](https://www.youtube.com/watch?v=Z0yLerU0g-Q)

## Wireframe

User experience

Cuál es la experiencia final que va a tener el usuario

tener las entrevistas y las personas—> Ofrecer las mejores soluciones

Representación de baja fidelidad

- Bloques de Contenido
- Estructura información
- Descripción de la interación

[https://www.youtube.com/watch?v=BRuNwXAGEG8](https://www.youtube.com/watch?v=BRuNwXAGEG8)

Un prototipo es funcional

Para los requerimientos voy a usar

- Clases—> vista lógica

Cliente—-Usuario

Administrador

Información de pago 

Formulario demanda

- Actividades—> vista de proceso

- Despliegue—>vista física
