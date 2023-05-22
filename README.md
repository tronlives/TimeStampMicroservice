
# API Project: Timestamp Microservice for FCC
[![Run on Repl.it](https://repl.it/badge/github/freeCodeCamp/boilerplate-project-timestamp)](https://timestamp-microservice.andradeoromulo.repl.co/)

## About
This is my project of the [Timestamp Microservice challenge](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice) for the freeCodeCamp API and Microservice certification. It was built based on the boilerplate available [here](https://github.com/freeCodeCamp/boilerplate-project-timestamp/).

## Endpoints:

Endpoints | Description
----------|-------------
GET `/api/timestamp` | Return a date object with unix timestamp and UTC timestamp of the current timestamp
GET `/api/timestamp/{dateParam}` | Return a date object of the informed timestamp (unix or UTC ISO-8601)

#### Example usage:
* https://timestamp-microservice.andradeoromulo.repl.co/api/timestamp
* https://timestamp-microservice.andradeoromulo.repl.co/api/timestamp/2015-12-25
* https://timestamp-microservice.andradeoromulo.repl.co/api/timestamp/1451001600000

#### Example output:
* `{"unix":1451001600000, "utc":"Fri, 25 Dec 2015 00:00:00 GMT"}`
* `{"error" : "Invalid Date" }`

## How to use:
Just run on terminal:
```
npm install
npm start
```

## Feedback
I'm a student and I really would like to hear case you have any tips, correction suggestions or comments about any my of projects (🤓).


