> Use Composer to install Sulu’s dependencies:

composer install

At the end of the installation, Composer asks you to submit values of different parameters. For now, just press “Enter” to keep their default values


To load the fixtures :
app/console sulu:build prod


If you want to also create a user with the credentials admin/admin you can also execute the following command:

app/console sulu:build dev

To start the server use the following command:
app/console server:start

You can access the administration interface via http://127.0.0.1:8000/admin. The default user and password is “admin”. 