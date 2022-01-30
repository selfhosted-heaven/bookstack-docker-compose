# BookStack in Docker Compose
## Introduction
This repository contains a Docker compose file for running BookStack. It contains a sample file with some variables that can be changed to your liking.


## Preparation
The `docker-compose.yml` file can be downloaded and placed on a location of your liking. Make sure to have a separate folder for the configuration files and a place to store your downloads. You should definitely change the passwords in the Docker Compose file to something more secure. 

## Starting It Up
You can launch the file with `docker-compose up`. After it has finished starting, which should not take very long, you can go to your browser and check if it is running properly.
You can check by going to `127.0.0.1:6543` if you're on the same machine. Replace `127.0.0.1` with the ip address in question if you have it hosted on another machine

After you are sure that it all works, you can keep BookStack running in the background, just run `docker-compose up -d`.

## First Time Usage
The first time you start Bookstack up, you will be greeted with a login screen. The default credentials are as follows:

Username: `admin@admin.com`
Password: `password`

You should change that as soon as possible.

## For More Information
For a more in depth guide on how this works, you can go to [selfhostedheaven.com](https://selfhostedheaven.com/posts/20220130-personal-wiki-bookstack/).
