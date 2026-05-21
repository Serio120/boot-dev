<h2 align=center>********* LABORATORIO DESBLOQUEADO *********</h2>

#  Aprende infraestructura en la nube con AWS

¡Bienvenido a "Aprende Infraestructura Cloud con AWS"! En este curso, aprenderás cómo funciona realmente "la nube", desde los servidores que alimentan tus aplicaciones hasta los sistemas de red, almacenamiento e identidad que las mantienen fiables y seguras. Utilizaremos Amazon Web Services (AWS) para aprender estos fundamentos, porque es la plataforma en la nube más utilizada en el mundo.

## Objetivos de aprendizaje

- Aprende los conceptos fundamentales de la computación en la nube y en qué se diferencia de la infraestructura local.
- Comprende las principales ofertas y productos de los grandes proveedores de nube, con especial atención a AWS.
- Adquiere experiencia práctica desplegando infraestructura en una cuenta de AWS y utilizando la interfaz de comando de AWS.

## Boot.dev CLI

A lo largo de este curso, usarás la Boot.dev CLI para ejecutar nuestras pruebas (que son solo comandos CLI) contra tu entorno local. Instálala ahora si no la tienes ya. Todas las instrucciones e información de solución de problemas están en la página de GitHub.

<h2 align=center>********* POR COMPLETAR, TRADUCIR Y MAQUETAR ENLACES *********</h2>

To verify your installation:

bootdev --version

If you're stuck, reach out in the help forums of our Discord server.

Once the command is working, log in and follow the instructions:bootdev

bootdev login

Run vs. Submit
Lessons have a series of commands that run on your local machine, and tests that check the results. There are two modes for running commands with the CLI, and :runsubmit

bootdev run <id>: Runs the commands and shows the results. This is meant to be used for debugging, but it won't tell you explicitly whether or not you've passed the tests.
bootdev run <id> -s: Runs the commands and gives you pass/fail feedback. On success, this will also mark the lesson as complete in the Boot.dev web app. If you get it wrong, though, you'll potentially lose your sharpshooter spree, so be sure to use first!run
You can copy the run/submit commands with the ready-to-go from the pane on the right.id

Docker
Later in the course, we will use Docker containers which will require to be installed locally. If you've never used Docker before, you should take our course on Docker.docker

Assignment
Let's make sure your Boot.dev CLI setup works end to end.

Run the lesson command and confirm your terminal output.

Copy the run command from the right panel and execute it in your terminal.
Confirm the output includes young developer yells at cloud.
Run and submit the CLI tests.
