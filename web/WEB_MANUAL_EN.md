# Web Boberto launcher manual

### ENGLISH

In this file, you will learn the basics of how the boberto launcher web part works and a brief explanation of each important implementation


1. Clone the project https://github.com/brutalzinn/boberto-launcher-web
2. Change the name of .env.example to .env
3. Configure an environment variable with your settings. Don't worry about bank passwords or things like that. Docker downloads all the services the project needs to run. So just worry about setting up the .env file with your data.
4. Run the docker-compose up command
5. Access http://127.0.0.1/teste.php in the browser
6. See if you got an OK
7. Test the http://127.0.0.1:5000 api with the postman tool. The collection is available there. This api will be used by the modpack manager.
8. Download the client for Redis and make sure it is correct.
9. Open the launcher and see if it is responding.
