Week3Exercise2


To Run:
$ docker run -d --name <container-name> -p 84:8000 ambikabs/week3exercise2

To log the port rsponse:
$ curl -o <filename.txt> http://localhost:84

To log the port activity:
$ docker logs -f <container-name>  >  <filename.txt>
