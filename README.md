[![Travis](https://img.shields.io/travis/rakshans1/docker-nodejs-yarn.svg)](https://travis-ci.org/rakshans1/docker-nodejs-yarn)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/nodejs-yarn.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/nodejs-yarn/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/nodejs-yarn/latest.svg)]()


![rakshans1/nodejs-yarn](/icon.png?raw=true)
# Latest Node.js with yarn
### based on [Nodejs latest](https://github.com/rakshans1/docker-nodejs)
----
### Pull from Docker Hub
```
docker pull rakshans1/nodejs-yarn:latest
```

### Build from GitHub
```
docker build -t rakshans1/nodejs-yarn github.com/rakshans1/docker-nodejs-yarn
```

### Run image
```
docker run -it rakshans1/nodejs-yarn bash
```

### Use as base image
```Dockerfile
FROM rakshans1/nodejs-yarn:latest
```