This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## WHY
This is a quick sample to run a base react app inside docker both in development and production mode

### HOW

The `.env` file has a variable `APP_ENV` that sets the way the container is built if set to a value different than `production` it build the image with the react app in development mode otherwise is built in production mode.

Supports Hot-reloading in development mode.

### BUILD
Just run `docker-compose build` in the root folder with the desired environment.  
(Ex: `APP_ENV=development`) 

## RUN

`docker-compose up` in the root folder

use the `-d` flag to run in detached mode

#### Have Fun
