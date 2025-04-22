FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update && apt-get install -y python3-pip


RUN su node -c "npm install -g @vue/cli"

RUN pip3 install flask