# .devcontainer/Dockerfile

FROM mcr.microsoft.com/dotnet/sdk:8.0

# Install essential tools
RUN apt-get update && apt-get install -y \
    curl \
    git \
    unzip \
    vim \
    && rm -rf /var/lib/apt/lists/*

# Set default working directory
WORKDIR /workspace
