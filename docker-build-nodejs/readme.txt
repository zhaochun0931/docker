docker build -t myapp .


docker run --rm -d --name myapp -p 8888:8080 -it myapp


$ curl localhost:8888
You've hit 7dc58d7639c2
$




# push to docker hub
docker login
docker tag myapp Your_docker_account_username/myapp
docker push Your_docker_account_username/myapp

