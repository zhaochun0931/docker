
docker image build -t mynodejs .


docker run --rm -d --name mynodejs -p 8888:8080 -it mynodejs


$ curl localhost:8888
You've hit 7dc58d7639c2
$
