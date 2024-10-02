# Reinforcement Learning 

## How to run:
```
docker compose up jupyter
```
This should launch a jupyter lab instance in the browser. The token is `my-token`, as specified in the docker-compose file. 

We mount the current directory to the docker setup, so all updates to the notebook are directly written to disk, and we can use git from the host machine. 