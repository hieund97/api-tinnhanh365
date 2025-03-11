# Project Name: api-tinnhanh365

## Setup Docker

1. **Install Docker**: Make sure you have Docker installed on your machine. You can download it from [here](https://www.docker.com/products/docker-desktop).

2. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/api-tinnhanh365.git
    cd api-tinnhanh365
    ```

3. **Build the Docker Image**:
    ```sh
    docker build -t api-tinnhanh365 .
    ```

4. **Run the Docker Container**:
    ```sh
    docker run -d -p 8000:8000 --name api-tinnhanh365-container api-tinnhanh365
    ```

## How to Run

1. **Access the Application**:
    Open your web browser and go to `http://localhost:8000`.

2. **Stopping the Container**:
    ```sh
    docker stop api-tinnhanh365-container
    ```

3. **Removing the Container**:
    ```sh
    docker rm api-tinnhanh365-container
    ```

## Additional Commands

- **View Running Containers**:
    ```sh
    docker ps
    ```

- **View All Containers**:
    ```sh
    docker ps -a
    ```

- **Remove Docker Image**:
    ```sh
    docker rmi api-tinnhanh365
    ```

## Troubleshooting

- If you encounter any issues, make sure Docker is running and you have followed all the steps correctly.
- Check the logs of the container for any errors:
    ```sh
    docker logs api-tinnhanh365-container
    ```
