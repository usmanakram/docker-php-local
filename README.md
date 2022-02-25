# docker-php-local
A simple docker workflow to setup LEMP network of containers for PHP development.

## Usage
To get started, make sure you have Docker installed on your system.

Clone this repository and put your PHP source code in `src` folder.

Now you need to run the application containers. (Don't worry, I'm here with you to guide further steps)
Open a terminal and goto root folder of this newly cloned repository and run `docker-compose up -d`.
Now, open up your favourite browser to [http://localhost:8080](http://localhost:8080) and you should see your code running as intended.

To view database, I have added phpMyAdmin. Open up browser to [http://localhost:8090](http://localhost:8090).
