# Daily Learning Progress – 20 November 2026

## 1. Linux – Filtering Text Streams Using grep

**Learning Platform:** Pluralsight

Topics covered:

- Understanding grep basics.
- Executing precision filtering using grep.
- Using grep with special characters.
- Understanding how grep helps search and filter text from files and command outputs.

### Practical Commands

```bash
# Search for a specific word
grep "error" application.log

# Case-insensitive search
grep -i "error" application.log

# Display line numbers
grep -n "error" application.log

# Search for an exact word
grep -w "error" application.log

# Search using special characters
grep "^error" application.log

# Search lines ending with a specific word
grep "failed$" application.log

# Invert the search
grep -v "success" application.log
```

## 2. Docker – Containerization Fundamentals

**Learning Platform:** YouTube

Topics covered:

- Understanding Docker fundamentals.
- Creating Dockerfiles.
- Building Docker images.
- Understanding containerization.
- Learning how to create and run Docker containers.
- Exploring the basics of microservices architecture.

### Practical Docker Commands

```bash
# Check Docker version
docker --version

# Build Docker image
docker build -t my-app .

# List Docker images
docker images

# Create and run a container
docker run -d -p 8000:8000 --name my-container my-app

# List running containers
docker ps

# View container logs
docker logs my-container

# Stop a container
docker stop my-container
```

## 3. Key Takeaways

- Learned how to filter text efficiently using grep.
- Understood precision filtering and special characters.
- Explored Dockerfile creation and image building.
- Understood the fundamentals of containerization.
- Started exploring microservices architecture.

## 4. Next Learning Goals

- Practice advanced grep commands.
- Explore regular expressions in Linux.
- Create a Dockerfile for a Python application.
- Understand Docker volumes and networks.
- Explore Docker Compose and microservices communication.
