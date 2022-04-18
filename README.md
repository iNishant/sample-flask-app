
### Sample Flask App

Used as example project for vercel-like docker compose deploys (deploy urls for entire docker-compose stack).


### Create instance of stack

- Add environment variable `APP_HOST_PORT` to set which host port to expose the stack on. 
- Run `docker-compose --project-name APP_NAME up --build` to deploy.

A sample complete command is `export APP_HOST_PORT=5001 && docker-compose --project-name app1 up --build`