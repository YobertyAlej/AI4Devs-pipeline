# Prompts (Claude Sonnet 3.7 + Thinking)

## Prompt 1
Eres un brillante devops engineer, con mas de 10 años de experiencia en configurar el uso correcto de EC2 Instances en AWS y el despliegue automatico de código usando Github Actions

Para esto se te ha asignado la tarea de Configurar en el Panel de IAM

Los usuarios deben estar debidamente configurados para crear Key Pairs secrets que acompañen el proceso
Eventualmente creare 5 secrets:

- AWS_ACCESS_ID
- AWS_ACCESS_KEY
- EC2_SSH_PRIVATE_KEY
- EC2_INSTANCE
- EC2_USER

Entregame una serie de pasos para configurar esto correctamente, dandome consejos de seguridad en el proceso, toma en cuenta que soy novato en el tema de DevOps

## Prompt 2

¿Esta bien esta configuración?
[Inserta imagen de referencia de la pantalla de configuración de personas de AWS]

## Prompt 3

¿es correcto este usuario?
[Inserta imagen de referencia de la pantalla de persona ya creada de AWS]

## Prompt 4

Ayudame a configurar la creación de la instancia de EC2
¿Que opciones deberia escoger?
[Inserta imagen de referencia de la pantalla de creación de instancia de EC2 de AWS]

## Prompt 5

Eres un experto en devops engineering, tu tarea sera configurar la creación de un pipeline en GitHub Actions que nos permitirá pasar unos tests de backend, generar un build y desplegar el backend en un EC2. El pipeline se disparará con un push a una rama con un Pull Request abierto.

Tu misión en este ejercicio es crear un pipeline en GitHub Actions que, tras el trigger "push a una rama con un Pull Request abierto", siga los siguientes pasos:

- Pase unos tests de backend.
- Genere un build del backend.
- Despliegue el backend en un EC2. 

Para ello, debes seguir estos pasos:

- Revisar el proyecto completo para entender como funciona especialmente los archivos @package.json , @package.json y @package.json 
- Configurar el workflow de GitHub Actions en un archivo .github/workflows/pipeline.yml.
- Documentar los prompts utilizados para generar cada paso del pipeline:
    - Tests de backend.
    - Generación del build del backend.
    - Despliegue del backend en EC2.

Asegúrate de que el pipeline se dispare con un push a una rama con un Pull Request abierto.

Dentro del repositorio en Github ya estan configurados los siguientes secrets que te comparti en la imagen:

- AWS_ACCESS_ID
- AWS_ACCESS_KEY
- EC2_INSTANCE
- EC2_SSH_PRIVATE_KEY
- EC2_USER

Recuerda no suponer nada, y aclarar todas tus dudas primero conmigo

## Prompt 6

Discutamos la solución prevista para ver si es adecuada para nuestra solución, para esto tengamos un enfoque critico, utilizando las mejores practicas disponibles pero sin complicar en exceso el despliegue

## Prompt 7

Dame un commit description comprensivo sobre lo que se logro