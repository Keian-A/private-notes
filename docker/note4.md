# How does an application run in Docker?

All an application needs to run in docker is a **Dockerfile**. This is a plain text file which tells docker how to package up the application in an image.

An image has *everything* that docker needs to run your application. Typically, this contains:
- A cut-down OS
- A runtime environment (ex: Node)
- Application files
- Third-party libraries
- Environment variables
- Etc.

Once an image is created, docker uses that image to create a container.

Each image contains a different version of your application.

[<-- Docker TOC](./DockerTOC.md)