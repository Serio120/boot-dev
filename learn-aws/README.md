#  Aprende infraestructura en la nube con AWS

¡Bienvenido a "Aprende Infraestructura Cloud con AWS"! En este curso, aprenderás cómo funciona realmente "la nube", desde los servidores que alimentan tus aplicaciones hasta los sistemas de red, almacenamiento e identidad que las mantienen fiables y seguras. Utilizaremos Amazon Web Services (AWS) para aprender estos fundamentos, porque es la plataforma en la nube más utilizada en el mundo.

## Learning Goals

Learn the fundamental concepts of cloud computing and how it differs from on-premises infrastructure.
Understand the major offerings and products of the large cloud providers, with a focus on AWS.
Gain hands-on experience deploying infrastructure in an AWS account and using the AWS CLI.
for Windows Users
If you try to complete this course without WSL 2 installed on Windows, you're gonna have a bad time.

Boot.dev CLI
Throughout this course, you'll be using the Boot.dev CLI to run our tests (which are just CLI commands) against your local environment. Install it now if you don't have it already. All the instructions and troubleshooting info are on the GitHub page.

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
