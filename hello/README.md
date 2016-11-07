# readytalk/nodejs-hello

[`readytalk/nodejs-hello`](https://index.docker.io/u/readytalk/nodejs) is a [docker](https://docker.io) image for the [express](http://expressjs.com/) [hello world](http://expressjs.com/guide.html) application.

It is based on [`readytalk/nodejs-runtime`](https://index.docker.io/u/readytalk/nodejs-runtime) base image and listen on port `8080`.

## Usage

- Run the following command

        docker run -p 8080:8080 readytalk/nodejs-hello
