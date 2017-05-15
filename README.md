# GRAV Dockerized

A docker image for starting with [Grav CMS](http://github.com/getgrav/grav).

## Quick guide

### Docker

This image is available on docker hub, then the simplest way to try it with docker alone is:

```
docker run -d -p 80:80 andreaschiona/grav-dockerized
```

Grav will be available on [http://localhost/](http://localhost/)

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

Now you have a fresh GRAV CMS with Admin Plugin installation.
Open your browser at `localhost` and you can see the following page:

![Admin Page](docs/screenshots/adminpage.png)


For use Grav see the [lean documentation](https://learn.getgrav.org/)
