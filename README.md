# demo spring boot rest service deployed with JIB

mvn compile jib:dockerBuild

docker run -p 8080:8080 jmge/demo-jib:latest

curl localhost:8080/api/users/1