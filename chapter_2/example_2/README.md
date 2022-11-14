##Building Application Images with Docker

1. Install Express

```
npm install express --save
```

2. Package this up as a Docker image

Dockerfile is a recipe for how to build the container image

.dockerignore defines the set of files that should be ignored when copying files into the image

3. Running the following command to create the simple-node Docker image

```
docker build -t simple-node .
```

4. To run the image in port 3000

```
docker run --rm -p 3000:3000 simple-node
```
