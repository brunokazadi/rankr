## Running the application

In order to run the application, you will need to have some prerequisite tools installed. 

First, you'll need to be able to run `docker-compose` command. If you are able to install Docker with Docker Desktop, that is probably the easiest solution.

Second, you'll need NodeJS for both the client and server applications. I recommend you use [nvm](https://github.com/nvm-sh/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows) and make sure to use the same version of node found in the [.nvmrc](/.nvmrc) file at the root of the project. You can run `nvm use` from the root of the project to make sure you're using the same version of node as me. 

With the everything installed and with Docker running on your machine, you can launch a docker container running `redis-json`, the backend Nest JS application, and the front-end react application by running the following from the root of the project.

```sh
npm run start
```

The project root's `package.json` file and its npm scripts are basically just for convenience of running all applications and a database at once.

You can also run these applications separately by running the appropriate npm scripts inside of each project's `package.json` file. 


## Links to Tools and Frameworks

### General
* [Typescript](https://www.typescriptlang.org/)
* [Docker](https://www.docker.com/products/docker-desktop)
* [Prettier](https://prettier.io/)
* [ESLint](https://eslint.org/docs/user-guide/getting-started)

### Frontend Application
* [Vite](https://vitejs.dev/)
* [React](https://reactjs.org/)
* [Valtio](https://github.com/pmndrs/valtio)
* [Wouter](https://github.com/molefrog/wouter)
* [Storybook](https://storybook.js.org/)
* [Socket.io Client](https://socket.io/docs/v4/client-api/)
* [Tailwind CSS](https://tailwindcss.com/)
* [react-use](https://github.com/streamich/react-use)

### Backend Application
* [NestJS](https://nestjs.com/)
* [Socket.io Server](https://socket.io/docs/v4/server-api/)
* [Redis-JSON](https://oss.redis.com/redisjson/)
* [Redis-JSON Docker Image](https://hub.docker.com/r/redislabs/rejson/)
* [JSON Web Token](https://jwt.io/)
