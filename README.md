## React Compose boilerplate application

This is the boilerplate code for a React app with TS.
It is containerized with Docker and archicted in a way that makes it easy to add other apps/dependencies, such as a backend or a microservice (you just need to add the code as a new folder in the root, add a Dockerfile to it and add a target to the `compose.yml` file).

### Use with Docker

No need to install anything but Docker here.
Just run `docker compose up` and start coding.