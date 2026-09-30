# 🚀 DevOps Automation Sandbox

Welcome to my DevOps playground! This project is a hands-on sandbox where I practice foundational Linux system administration, bash automation, Git collaboration workflows, and modern CI/CD pipelines. 

The goal of this project is to simulate real-world infrastructure tasks—like managing environments, handling configurations securely, and automating testing before code hits production.

## 🛠️ What's Inside?

*   **`config.env`**: A centralized environment configuration file used to toggle application states between testing, staging, and production environments.
*   **`deploy.sh`**: A lightweight, executable Bash automation script that reads configuration states dynamically and simulates system deployment flags.
*   **`.github/workflows/ci.yml`**: A continuous integration pipeline that automatically spins up a virtual runner to test and validate script execution on every code update.

## 🚀 How to Run It Locally

### 1. Prerequisites
Ensure you are using a Linux/Unix environment (or a local terminal on macOS/WSL) and have Git installed.

<img width="832" height="263" alt="image" src="https://github.com/user-attachments/assets/30f23d0c-6789-4105-ad2e-9454e2486888" />

### 2. Execution Steps
Clone the workspace and run the automated deployment script directly from your terminal:

```bash
# Make sure the script has execution rights
chmod +x deploy.sh

# Run the deployment routine
./deploy.sh
```

## 🧠 DevOps Concepts Demonstrated

*   **Linux Foundations:** Working inside an Ubuntu server environment, managing standard file pathways, and writing modular shell tools.
*   **Access Control:** Implementing strict file permission boundaries using symbolic/octal notation (`chmod`) to ensure administrative scripts are locked down.
*   **Advanced Git Workflows:** Navigating branch structures, resolving manual upstream merge conflicts safely, and maintaining a deployable production line.
*   **Continuous Integration (CI):** Structuring declarative automation architecture (YAML) to trigger event-driven testing suites inside cloud-hosted GitHub Actions runners.
<img width="397" height="146" alt="image" src="https://github.com/user-attachments/assets/d8805f18-cb4f-4006-a689-283fcc796819" />
