{
  "name": "rd-agent-mle DevContainer",
  "image": "mcr.microsoft.com/devcontainers/python:3.11",
  "workspaceFolder": "/workspaces/RD-Agent",
  "remoteUser": "root",
  "customizations": {
    "vscode": {
      "extensions": [
        "ms-python.python",
        "ms-python.vscode-pylance",
        "ms-toolsai.jupyter"
      ]
    }
  },
  "postCreateCommand": "pip install -e . && pip install -r requirements.txt"
}
# 2. (Optional) install any additional tools you need
#    e.g. git, bash-completion, etc.
# RUN apt update && \
#     apt install -y git bash-completion && \
#     rm -rf /var/lib/apt/lists/*
RUN apt update && \
    apt install -y git bash-completion
