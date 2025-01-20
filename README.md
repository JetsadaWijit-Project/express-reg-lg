## Info

`This is a Node.js project using the Express framework to create a sample registration and login system`

<hr>

# `Tools`
`Docker`

## Environment Variables (needed)
`PORT` = `3000`

`SESSION_SECRET` = `node -e "console.log(require('crypto').randomBytes(256).toString('hex'))"`

# Running the Project

We use a `Dockerfile` to run this project for testing. Follow these steps:

- docker build -t {image} .
- docker run -d -p {port}:{port} {image}

image is the name of the service, which we will set as the project name.

port is the port number used to run the server.

# `Member`

|Role|User|Email|Website|
|-|-|-|-|
|owner|[JetsadaWijit](https://github.com/JetsadaWijit)|jetsadawijit@outlook.com|[Profile](https://jetsadawijit.github.io)|
