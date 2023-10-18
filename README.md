# html-docker-test

>  small documentation for docker and containers learning

## Docker

## What is docker? 

Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications.

## What is a container or containers?

Containers are packages of software that contain all of the necessary elements to run in any environment. In this way, containers virtualize the operating system and run anywhere, from a private data center to the public cloud or even on a developer's personal laptop.


So, basically with containers we can access - and of course, also create images and do that - any application, system etc no matter it's OS, device.
It's something, may I say, revolucionary, and big companies are already using it every day.


## Here some commands:

- [x] docker run -p 8080:80 -v (volum) $/file -> run docker and save share you app to not lost data
- [x] docker-compose up -d -> docker-compose runs automatically all services
- [x] docker ps -> see info about containers (id, image, command, port...)
- [x] docker exec 'container name' ls -> list directories (inside container)
- [x] docker exec -it (interactivy mode) 'container name' bash -> get into container
- [x] cat index.html -> list html of nginx (or other, if it has)
- [x] rm -f index.html -> remove file
- [x] echo "hello world" > index.html -> create file
- [x] docker build -t 'dockerhubname'/'project-name':latest -> run build
- [x] docker push 'image-name' -> share image on dockerhub - allow others to experiment it.

## 🔧 Versioning
- [x] Version 1.0:

## :rocket: Technologies ##

- [Docker](https://www.docker.com/)

## :closed_book: Requirements ##

Before begin :checkered_flag:, you have to got [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/marcusvinicius0/html-docker-test
# Access
$ cd html-docker-test
# Install dependencies
$ yarn or npm 
# Run the project
$ yarn start or npm start 
# The server will initialize in the <http://localhost:3000>
```
<a href="#top">Get back to top</a>

## References: 

docker: https://docs.docker.com/get-started/overview/
<br>
containers: https://cloud.google.com/learn/what-are-containers?hl=pt-br#:~:text=Containers%20are%20packages%20of%20software,on%20a%20developer's%20personal%20laptop.
