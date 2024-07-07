# DevOps example app

![CI status](https://github.com/hexlet-components/devops-example-app/actions/workflows/main.yml/badge.svg) [![Count docker images pulls](https://img.shields.io/docker/pulls/hexletcomponents/devops-example-app.svg)](https://hub.docker.com/r/hexletcomponents/devops-example-app)

This is a simple node application that shows on the main page server on which it is running and report errors to [Rollbar](https://rollbar.com/).

## Usage

```bash
docker run -p 8080:8080 -e NODE_ENV=development antmbx/devops-for-programmers-project-74 make dev

# open http://0.0.0.0:8080 in browser
 ```

Edit *.env* file to set up environment variables.

```env
DATABASE_HOST=[db host]
DATABASE_NAME=[db name]
DATABASE_USERNAME=[db username]
DATABASE_PASSWORD=[db password]
```


![Screen of example-app](assets/app.png)

---
