# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is a system that has two main parts: the **web/application tier** and the **database tier**. These two parts work separately but communicate with each other through a network. This makes the system easier to manage and update.

## The Web/Application Tier

The web/application tier is responsible for:
- Showing the website to users
- Receiving requests from web browsers
- Handling the main functions of the application
- Connecting to the database to get or save information

In our deployment, **Nextcloud** is used in this tier. It receives requests from the browser through port 8080 and displays the Nextcloud website. It also gets information from the database.

## The Database Tier

The database tier is responsible for:
- Storing user accounts and other important data
- Managing information using SQL
- Keeping the data safe and organized

In our deployment, **MariaDB 10.6** is used in this tier. It runs inside the Docker network and only allows the Nextcloud container to connect to it.

## Why Separate Them?

Separating the web application and database into two containers makes the system more organized and secure. If the Nextcloud container has a problem, the database can continue running without losing the stored data.

It also makes it easier to update or manage each part separately. For example, we can add more Nextcloud containers when more users need to access the system. Keeping the database separate also improves security because it is not directly exposed to the internet.
