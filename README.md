Just cd into directory and run:

docker-compose up -d

to stop:

docker-compose down

NOTE: In order for the app to work you will have to create a database named "company1", a "users" table with the columns "name" and "fav_color" in order for the errors to go away.

You can do this in localhost:8080  (adminer) with "root" as user, "example" as password.  "MySQL" selected for the system, and "db" as the server.

Then create the database & table and you should be able to see the php grab the users and display them.

https://truthseekers.io/php-docker-simple-environment/ blog post.
