# Trivy-Scanner

# Installing Docker from the Default Repositories 
## Step 1: Update the Repository
Ensure that the local system package repository is updated by running:
  1. sudo apt update

## Step 2: Install Docker
Run the following command to install Docker:
  2. sudo apt install docker.io -y

## Step 3: Install Dependencies
Install all the Docker dependency packages by running the following command:
  3. sudo snap install docker

## Step 4: Check Installation
Check whether Docker was properly installed by running the status command or checking the program version. To see the Docker daemon status, run:   
  4. sudo systemctl status docker
  5. docker --version

