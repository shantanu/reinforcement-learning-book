# Reinforcement Learning 

## How to run:
```
docker compose up jupyter
```
Once this is up, launch `localhost:8888` in your browser, which should forward to the jupyter lab instance in the container. The token is `my-token`, as specified in the docker-compose file. 

We mount the current directory to the docker setup, so all updates to the notebook are directly written to disk, and we can use git from the host machine. 