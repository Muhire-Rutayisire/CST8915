### 1. What are the main differences between a Docker image and a Docker container?
- A Docker image is like a recipe that has all the instructions and ingredients needed to run an app. A container is the actual running app made from that recipe. The image stays the same, while containers can be started, stopped, or removed anytime.

### Explain how Docker’s layered architecture improves efficiency.
- Docker builds images in layers, like stacking blocks. If something changes, only the top layer needs to be updated instead of rebuilding everything. This makes it faster, saves space, and lets different images share the same layers.

### 3. Why does each container get its own writable layer?
- Each container has its own writable layer so it can save changes, like logs or temporary files, without touching the original image. This way, the base image stays clean, and every container can work separately without affecting others.

### 4. What are the benefits of using Docker Compose over running containers individually?
- Docker Compose makes it easy to run apps that need many containers. Instead of starting each one by hand, you write all the setup in one file and then start everything with a single command. It keeps things organized and consistent.

### 5. Demo video
- [Video](https://youtu.be/ZOlMKJaMGtM)
