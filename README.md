# TO DO LIST Project

## Intro

This project aims at learning, so far using one of the most popular frameworks for backend development in Javascript: Node.js.

## Enviroment

So far we have used three basic libraries for development:

- dotenv versão 16.3.1;
- express versão 4.18.2;
- mysql: versão 3.6.0

## Running the Project

1. First have node installed in version 18 or higher;
2. Inform some environment variables that are exemplified in the .env.example file in the /src directory; 
3. Create a file called .env (following the example mentioned in the previous step) in the /src directory and inform the port on which the API will be executed and the information concerning the connection to the database;
4. Run the following command to get all the dependencies needed to run the project:

```bash
npm install
```

5. That will be enough for the execution, run the following command to run the project:

```bash
npm start
```

6. The API will be executed through the port informed in the .env file, now just type in the web browser of your choice the following url: http://localhost:{port in execution}/tasks.