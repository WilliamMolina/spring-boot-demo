# Spring Boot Demo

## Build

mvn compile "-Drelease.version=1.0" jib:dockerBuild

## Build and pusblish

mvn compile "-Drelease.version=1.0" jib:build

## Test

curl -X GET http://localhost:8080/hello/william