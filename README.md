# n8n Quickstart
> Setup n8n locally in a Docker container

This project makes it easy to setup n8n locally in a container and to persist the data outside the container.

See [n8n](https://n8n.io/) website for more info.


## Prerequisites

- Install [Docker](https://www.docker.com/) or a Docker alternative.
- Install [Ollama](https://ollama.com/) and start it on the host.


## Start service

```sh
$ docker compose up
```

Then open at:

- http://localhost:5678/

Follow this guide to configure n8n to access Ollama:

- [Ollama docs - n8n](https://docs.ollama.com/integrations/n8n)
