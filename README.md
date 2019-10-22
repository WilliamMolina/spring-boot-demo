# Spring Boot Demo

## Build

mvn compile "-Drelease.version=1.0" jib:dockerBuild

## Build and pusblish

mvn compile "-Drelease.version=1.0" jib:build

## Run

docker run -it -p 8080:8080 demo:release.version

## Test

curl -X GET http://localhost:8080/hello/william