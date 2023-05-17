# 🫧YouTube Page Genarator🫧'

A Streamlit application that generates YouTube video titles and scripts based on a user's prompt. This application is containerized using Docker for easy setup and deployment.

## Prerequisites

- Docker: You must have Docker installed on your machine. Visit the [Docker website](https://www.docker.com/products/docker-desktop) for installation instructions.

## How to Run the Application

1. **Clone the Repository**

   Start by cloning this repository to your local machine. You can do this by running the following command in your terminal:

   ```bash
   git clone <repository_url>
   ```

   Replace `<repository_url>` with the URL of this GitHub repository.

2. **Navigate to the Project Directory**

   After cloning the repository, navigate into the project directory:

   ```bash
   cd <directory_name>
   ```

   Replace `<directory_name>` with the name of the directory where the repository was cloned.

3. **Build the Docker Image**

   Inside the project directory, build the Docker image by running the following command:

   ```bash
   docker build -t youtube_gpt_creator .
   ```

   This command tells Docker to build an image using the Dockerfile in the current directory (`.`) and tag it as "youtube_gpt_creator".

4. **Run the Docker Container**

   Once the image is successfully built, run the application in a Docker container with the following command:

   ```bash
   docker run -p 80:8501 youtube_gpt_creator
   ```

   This will start the container and map port 80 of your machine to port 8501 of the container (where the Streamlit app is running).

5. **Access the Application**

   You can now access the application by opening a web browser and navigating to `http://localhost`.

## License

This project is licensed under the terms of the MIT license.

## Contributions

Contributions, issues, and feature requests are welcome!
```

Remember to replace `<repository_url>` and `<directory_name>` with the URL of this GitHub repository and the name of the directory where the repository was cloned, respectively.