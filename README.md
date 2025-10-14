# 🚀 Python App with Docker & GitHub Actions CI/CD

This repository contains a simple **Python application** that is containerized using **Docker** and automatically deployed using **GitHub Actions** as part of a **CI/CD pipeline**.

### 💡 Workflow Overview

-  **Triggered on:** Push to the `main` branch test.txt file or on pull requests.
-  **Step 1:** Checks out the repository code  
- **Step 2:** Sets up Python and installs dependencies
- **Step 3:** Builds the Docker image
- **Step 3:** Builds the Docker image  
- **Step 4:** Runs tests (if configured)  
- **Step 5:** Pushes the Docker image to Docker Hub or GitHub Container Registry  
- **Step 6 (Optional):** Deploys to a remote server or cloud service
