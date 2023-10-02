# Password_Generator
You can use this app from : https://yucel-business-srl5tqspma-uc.a.run.app/

# Password Generator Web App

This is a simple web application for generating passwords with options for length, uppercase characters, numbers, and symbols. 
It is designed to be easily deployed using Docker and can be hosted on Google Cloud Run.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Google Cloud SDK: [Install Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
- Google Cloud Run enabled: [Enable Cloud Run](https://cloud.google.com/run/docs/quickstarts)

## Local Development

To run the application locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/password-generator-app.git
   cd password-generator-app

Build the Docker image:

docker build -t password-generator-app .
Run the Docker container:


docker run -p 8080:80 password-generator-app
Open your web browser and navigate to http://localhost:8080 to access the application.
