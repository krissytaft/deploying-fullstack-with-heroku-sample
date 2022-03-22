## Deploying a Full-Stack App with Heroku
Hello! This GitHub repo is intended to be used with the article [Deploying a Full-Stack App with Heroku](https://www.codecademy.com/articles/deploying-a-back-end-with-heroku).

Make sure to follow the steps as outlined in the article to see how to use Heroku for your deployment needs!

If you're curious about the app itself feel free to poke around. The server files are located in the root folder. The `/build` folder contains the production code that was created from the front-end folder found in `/client`.

You're free to make changes on your own branch, but for the sake of consistency, we will not be merging any external pull requests. Thank you and happy coding!


Starting up the local db: docker run -it -e "POSTGRES_HOST_AUTH_METHOD=trust" -e "POSTGRES_DB=kidkreddb" -p 5432:5432 postgres


Create table script: CREATE TABLE my_activities (activity text);