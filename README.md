# ollama-docker

A simple, repeatable, performant docker compose setup for ollama.

## Install and run

To install and run Ollama via docker, run the following command:

```docker compose -f 'compose.yml' up -d --build```

Then navigate to http://localhost:3000 to access Open WebUI.

Use http://localhost:8080 for API access, such as when using a Python deployment.
