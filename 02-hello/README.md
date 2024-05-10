## First part of the demo

- 👋 show the Dockerfile 🐳

```bash
docker build -t hello .
docker run -d -p 6060:8080 --name hello-container --rm hello
# I'm listening on the 8080 http port, I map the host 6060 port of the host on the container port
```
> - Open http://localhost:8080
> - Open http://localhost:6060



## Second part of the demo with the GUI

- Go to the Dashboard:
  - show container (Logs)
  - then Exec
    - ls
    - cat index.js
  - then Files

```bash
docker stop hello-container
```