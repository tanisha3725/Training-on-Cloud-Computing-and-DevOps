# 📘 DAY 5

## Containerizing a Simple Website

Today, we explored how a website can be packaged into a Docker image and run inside a container. This connected the concepts of 
application files, dependencies, images, and containers.

## What Is a Dockerfile?

A Dockerfile is a text file containing instructions used to build a Docker image. It can specify a base image, copy application files, 
install dependencies, and define how the application starts.

## General Workflow

1. Prepare the website source files.
2. Create a Dockerfile suited to the application.
3. Build an image from the Dockerfile.
4. Run a container using the image.
5. Configure port mapping if the application needs to be accessed from outside the container.
6. Test whether the website works as expected.

## How the Components Work Together

- **Application:** The website and its source files.
- **Dockerfile:** The instructions for building the image.
- **Image:** The packaged application environment.
- **Container:** The runtime instance created from the image.

## Key Learnings

- Understood the role of a Dockerfile.
- Learned the general process of building an image.
- Explored how a container can run a website.
- Connected containerization with application deployment.

## Conclusion

This session brought together the Docker concepts learned earlier and explained how containerization can be applied to a website project.
