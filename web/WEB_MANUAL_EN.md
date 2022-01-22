## Web Launcher Boberto part manual

### ENGLISH

In this file, you will learn the basics of how the web part of the boberto launcher works and a brief explanation of each important implementation


1. Clone the https://github.com/brutalzinn/boberto-launcher-web project
2. Change the name from .env.example to .env
3. Set the environment variable to your settings. Don't worry about bank passwords and stuff like that. Docker will download all the services the project needs to run. So just worry about setting up the .env file with your data.
4. Run the command docker-compose up
5. Go to http://127.0.0.1/ in the browser
6. See if you get an OK
7. Test the http://127.0.0.1 api with the postman tool. The collection is available in this same repository. This api will be used by the modpacks manager and in the future by the launcher.
8. Download a Redis client and check that it is working properly.
9. Open the launcher in development mode and check the console for bugs.
10. Web part configured.
