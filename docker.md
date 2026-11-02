# Docker cheat sheet

| Goal | Command |
|---|---|
| Build an image | `docker build -t name .` |
| Run and remove after exit | `docker run --rm -p 3000:3000 name` |
| List running containers | `docker ps` |
| Shell into a container | `docker exec -it <container> sh` |
| Start a compose stack | `docker compose up -d` |
| Clean unused data | `docker system prune` |
