<h1 align="center">Find My Coffee</h1>

<p align="center">
  <a href="#">
    <img alt="Current Version" src="https://img.shields.io/badge/version-1.0.0 -blue.svg">
  </a>
  <a href="https://ruby-doc.org/core-2.7.1/">
    <img alt="Ruby Version" src="https://img.shields.io/badge/Ruby-2.7.1 -brightgreen.svg" target="_blank">
  </a>
  <a href="https://edgeguides.rubyonrails.org/6_0_release_notes.html">
    <img alt="" src="https://img.shields.io/badge/Rails-~> 6.0.2-blue.svg" target="_blank">
  </a>
</p>

## API
![](https://github.com/Thiago-Cardoso/find_my_coffee/blob/master/find_my_coffee_web/public/images/find_my_coffee_api.gif)

## Web

![](https://github.com/Thiago-Cardoso/find_my_coffee/blob/master/find_my_coffee_web/public/images/find_my_cofffe_frontend.gif)


## Stack the Project

- **Docker**
- **Rails Api**
- **Postgis**
- **ReactJS**

## Features

- **Web - Lists the nearest establishment of cafes by city location and Option to evaluate the establishment

  
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have installed on your machine:

- Docker
- Docker Compose
- NPM or Yarn

### Installing

First step is to install the docker service:

```bash
#Linux: ubuntu,Mint
$ sudo apt-get update
$ sudo apt-get install docker-ce
$ sudo apt install docker-compose

# Fedora
$ sudo dnf update -y
$ sudo dnf install docker-ce
$ sudo dnf -y install docker-compose
```

For test if the service was installed with succeed, you can run the command for to check de version of docker:

```bash
$ docker --version
#Must be have the docker version: Docker version 18.06.0-ce
$ docker-compose --version
#Must be have the docker-compose version: docker-compose version 1.22.0
```

## First steps

Follow the instructions to have a project present and able to run it locally.
After copying the repository to your machine, go to the project's root site and:

1.  Construct the container

```
docker-compose build
```

2. Created database and run migrate for project API

```
docker-compose run --rm app bundle exec rails db:create db:migrate 
```

3.  Run the project API 

```
docker-compose up - d
```
The api run in the port 3000 -http://localhost:3000


4.  Run the project Web
```
npm install or yarn install
npm start or yarn start
```

The Web run in the port 3001 -http://localhost:3001

## Author

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
[<img src="https://avatars1.githubusercontent.com/u/1753070?s=460&v=4" width="100px;"/><br /><sub><b>Thiago Cardoso</b></sub>](https://github.com/Thiago-Cardoso)<br />
