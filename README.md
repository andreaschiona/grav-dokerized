# GRAV Dockerized

A docker image for starting with [Grav CMS](http://github.com/getgrav/grav).
For play with Grav see the [learn documentation](https://learn.getgrav.org/)

## Quick guide

### Docker

This image is available on docker hub, then the simplest way to try it with docker alone is:

```
docker run -d -p 80:80 andreaschiona/grav-dockerized
```

Now you have a fresh GRAV CMS with Admin Plugin installation.
The Grav simple web app will be available in [http://localhost/](http://localhost/).

The first time you have to create the admin user (for Admin plugin)

![Admin Page](docs/screenshots/adminpage.png)

## Clone and build instructions

Otherwise you can clone [this git repository](https://github.com/andreaschiona/grav-dokerized) and build your own image.

First of all clone this repo in your local file system:

```
git clone https://github.com/andreaschiona/grav-dokerized.git
```

Then, from the folder of the project, build the image with docker-compose

```
docker-compose build
```

And start the container with

```
docker-compose up
```

So, Grav will be available in [http://localhost/](http://localhost/).

