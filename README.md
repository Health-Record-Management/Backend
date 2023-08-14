# HMS BACKEND EXPRESS
This is the hms backend application implemented in javascript and typescript. It uses an already hosted online mongo database.

## Environmental Variables
Set the environmental variables in an .env file as follows:
```
PORT={Choosen Port}
MONGO_URI={URI from MongoDB}
MONGO_URI_TEST={Test URI from MongoDB}
```

## DEVELOPMENT
1. In order to run the application you would need to set environment variables for the application to use. The easiest way is to create a .env file for your development. Please take a look at the .env-example file, create a new file called .env, and copy the varialbles from .env-example to .env.
2. Run ```$ npm run dev``` in order to start the application in development.

## Tests
Run the tests using:
```shell
npm test
```

## PRODUCTION
1. Make sure all environment variables are present in the application from the .env-example file
2. Run ```$ npm build``` to build the project.
3. Run ```$ npm start``` to run the application in production