FROM python:3.11-slim

COPY ../requirements.txt /workspace/requirements.txt
# Install git and other dependencies
RUN apt-get update && apt-get install -y git && rm -rf /var/lib/apt/lists/*

# Set up work directory
WORKDIR /workspace

# Install dependencies
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# Default command
CMD ["sleep", "infinity"]