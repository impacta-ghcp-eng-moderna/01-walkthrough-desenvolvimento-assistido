FROM mcr.microsoft.com/devcontainers/dotnet:1-10.0

USER root

RUN apt-get update \
    && apt-get install --yes --no-install-recommends sqlite3 \
    && rm -rf /var/lib/apt/lists/*

USER vscode
