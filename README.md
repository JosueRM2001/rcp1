# RPC
This is a project that was developed with GO in an RPC architecture.

## Description
This project shows how a server and client work to execute the script.
It is a simple program to show how a program works in the programming language with an architectural style.

## Technologies Used
**Contains the Following**
- Visual Studio Code (most current version)
- Docker
- RPC
- GO (most current version)

## Development Requirements
- **Docker Desktop** (if you want to run it in a container)
- **Visual Studio Code** (optional, but recommended)
- **GO** (required and recommended)
- **The GO extension for Visual Studio Code** (for improved support and syntax highlighting).
- **GitHub Desktop** (if you want to clone and use the project)

```bash
https://www.docker.com/products/docker-desktop/
```

- **Docker hub** (if you want to clone and use the project)

```bash
https://hub.docker.com/layers/erickjrm/programrpc/latest/images/sha256-22d24c8d407e8ae11a809d78cfe189b0dd6354b2752e589b90600df140759ba3?context=repo
```

## Instructions to run the project
## Steps to run
**Step #1**
**Clone this repository**
If you have not yet cloned the repository, you can do so with the following link:

```bash
https://github.com/JosueRM2001/rcp1.git
```
**Step #2**
**Build the Docker Image**

Run the following command, which will build the image:

```bash
docker pull erickjrm/programrpc:latest
```

**Step #3**
**Run the Docker container:**

Then run the following command, which builds the container and port.

```bash
docker run -d -p 4000:4000 --name RPC erickjrm/programrpct:latest
```

**Step #4**

Open Docker Desktop to see if the image was built successfully and send it to run to view.

**Step #5**

**Access the application**: If it is running, you can access the application by navigating to the

following url in your web browser:

```bash
https://localhost:4000
```
