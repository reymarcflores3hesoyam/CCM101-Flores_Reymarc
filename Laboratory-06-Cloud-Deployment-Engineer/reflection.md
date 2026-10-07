# Mission 6 Reflection

For me, creating the `docker-compose.yml` file made the deployment easier. I only needed one file to set up the different containers. Instead of typing many commands one by one, I put the settings for Nextcloud and MariaDB in the file and ran them together. This made the process faster and more organized.

I learned that YAML needs the correct spacing and indentation. If I use a Tab or put the spaces in the wrong place, Docker Compose can show an error, and the containers may not start. This activity helped me understand why the format of the file is important.

We used environment variables like `MYSQL_PASSWORD` to help Nextcloud connect to the MariaDB database. We also added the database name, username, password, and host so the two containers could communicate properly.

I felt happy when I saw that both Nextcloud and MariaDB were running successfully. At first, I was worried that I might make a mistake in the YAML file. But when I saw the Nextcloud setup page, I felt relieved because I knew I had completed the activity correctly.

Since Mission 1, my understanding of Cloud Computing has improved. Before, I mainly thought that cloud computing was about using services through the internet. Now, I understand more about containers, databases, and deployment. I also learned how different services can work together and why Docker Compose is useful for running multiple containers.
