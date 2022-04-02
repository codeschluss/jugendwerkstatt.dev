# jugendwerkstatt.dev

All services started from a single repository

_Keep in mind this repository is for local development only and is not meant to be deployed on any production environment!_

## Requirements

1. [Docker](https://docs.docker.com/install/)
2. [Docker Compose](https://docs.docker.com/compose/install/)

## How to run it?

1. Clone the repository:

```
git clone https://git.sf-bleche.de/sf-bleche.dev --recursive
```

2. Shared folders:
   We are using shared folders to enable live code reloading. Without this, Docker Compose will not start: - Windows/MacOS: Add the cloned `jugendwerkstatt.dev` directory to Docker shared directories (Preferences -> Resources -> File sharing). - Windows/MacOS: Make sure that in Docker preferences you have dedicated at least 5 GB of memory (Preferences -> Resources -> Advanced). - Linux: No action required, sharing already enabled and memory for Docker engine is not limited.
