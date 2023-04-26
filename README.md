# openapi-mock
## use
1. stoplight/prism:4(docker image)
2. docker-compose : 3.9
3. openapi : 3.0.0

## setup
```
$ git clone git@github.com:You-saku/openapi-mock.git
$ cd openapi-mock
$ docker-compose up -d --build
$ curl --location --request GET 'http://0.0.0.0:4010/ok' --header 'Accept: application/json'
```
