RCSS-Tournament-Manager is a project that aims to provide a simple and easy to use tournament manager for the RoboCup Soccer Simulation 2D. 

If you want to know more about how this project works, you can read the [project documentation](https://github.com/RCSS-Tournament-Manager/docs).

## Project Parts
The project is divided to the following parts:

- **Manager Frontend** - `manager-frontend`

   A web application that provides a user interface for managing tournaments.

- **Manager Backend** - [`manager-backend`](https://github.com/RCSS-Tournament-Manager/manager-backend)

  A RESTful API that provides the backend for the manager frontend, all the logic for managing tournaments is implemented here.

- **Game Runner** - [`runner`](https://github.com/RCSS-Tournament-Manager/runner)

  The program that runs the games and sends the results to the manager backend.

- **Team builder** - [`team-builder`](https://github.com/RCSS-Tournament-Manager/team-builder)

  Service that build docker images for teams based on the team's binary code and sends them to docker registry.
