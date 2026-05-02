# n8n Docker Starter

Hello! I created and maintain this small repository to help my fellow students get started quickly with n8n. Feel free to clone, use, and update it to your personal needs.

Note that I only created a local setup in the "local" directory.
If you are interested in self-hosting, take a look at my [Portainer config repository](https://github.com/makoeta/stack-configs).

## Prerequisite

Of course, you will need Docker installed on your system to run the setup. If you have trouble installing it, take a look at this guide:

[Install Docker Engine](https://docs.docker.com/engine/install/)

## Running the local setup

1. Clone the repository
2. Use your terminal and go to the "local" directory
3. Run "docker compose up"

You're all set! n8n is now running locally at http://localhost:5678/.
Ollama is downloading the llama3.2:latest model. This may take a while, but you can set up the credentials for Ollama and Qdrant in n8n. To do so, set up your n8n, create your first workflow, and go to an Ollama or Qdrant node. Click on "+ Create new credentials". The URLs are as follows:

| application | url |
| ----------- | ----------- |
| Ollama | http://ollama:11434 |
| Qdrant | http://qdrant:6333 |

Have fun with your brand new local n8n instance!
