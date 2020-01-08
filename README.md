[![Build Status](https://travis-ci.org/jonathanabila/docker-python-nodejs.svg?branch=master)](https://travis-ci.org/jonathanabila/docker-python-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/jonathanabila/python-nodejs.svg?style=flat-square)](https://hub.docker.com/r/jonathanabila/python-nodejs/)
![](https://img.shields.io/microbadger/image-size/jonathanabila/python-nodejs.svg)
![](https://img.shields.io/github/license/jonathanabila/docker-python-nodejs.svg)

### Python 3.6.8 with Node.js 12.x based on [nikolaik/python-nodejs](https://github.com/nikolaik/docker-python-nodejs)

    Node: 12.x
    npm: 6.x
    yarn: stable
    Python: 3.6.8
    pip: latest
    pipenv: latest
    awscli: latest

### Python 3.7 with Node.js 12.x based on [nikolaik/python-nodejs](https://github.com/nikolaik/docker-python-nodejs)

    Node: 12.x
    npm: 6.x
    yarn: stable
    Python: 3.7
    pip: latest
    pipenv: latest
    awscli: latest

Pull from Docker Hub

```
docker pull jonathanabila/python36-nodejs
```

Build from GitHub
```
docker build -t jonathanabila/python36-nodejs github.com/jonathanabila/docker-python-nodejs
```

Run image

```
docker run -it jonathanabila/python36-nodejs bash
```

Use as base image

```
FROM jonathanabila/python36-nodejs:latest`
```

Disclaimer

    This is experimental and might break from time to time. Use at your own risk!
