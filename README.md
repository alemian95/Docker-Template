# Docker-Template

Base docker template to run php and mysql applications

# Before run it

- Go to the `docker-compose.yml` file and customize your database variables
- Default port is 8000, unless you get some conflicts there is no need to change it

# How to run it

- Create a public folder in the root directory
- Inside the public folder, create a `index.php` file and paste this code

`<?php phpinfo();`
  
- Open your terminal and run the command `docker-compose up --build`
- After the container is running open your browser and go to `localhost:8000`, if you see the output everything is fine
