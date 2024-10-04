# Project-Docker

This is my first Docker project, aimed at learning how Docker works. It's a simple landing page that, when clicked, navigates you to my project and main GitHub account.

## Project Details

- **Repository:** [shardendumishra22/projectdocker](https://hub.docker.com/r/shardendumishra22/projectdocker)
- **Docker Pull Command:**
  ```bash
  docker pull shardendumishra22/projectdocker:0.0.1.release
  ```

## Technologies Used

### Docker
![Docker Icon](https://raw.githubusercontent.com/docker/brand/master/img/2013/logo/logo-horizontal.png){: width="60" height="40"}

Docker is an open platform for developing, shipping, and running applications. It allows you to package an application with all its dependencies into a standardized unit called a container. 

### Key Features of Docker:
- **Isolation:** Each application runs in its own container, isolated from others.
- **Portability:** Containers can run on any system that has Docker installed, regardless of the underlying environment.
- **Scalability:** Easily scale applications by running multiple containers.

## Getting Started

1. Clone the repository or pull the Docker image using the provided command.
2. Run the container:
   ```bash
   docker run -d -p 3000:3000 shardendumishra22/projectdocker:0.0.1.release
   ```
3. Open your browser and navigate to `http://localhost:3000`.

## Contact

For any inquiries, please reach out to me on my [GitHub](https://github.com/ShardenduMishra22).
