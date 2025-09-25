# Gromacs_docker_setup

---

## 📦 Installation

### 1. Install Docker

#### Windows (via WSL)

```powershell
wsl --install
sudo apt-get update
sudo apt-get install docker.io -y
```

#### Linux

```bash
sudo apt-get update
sudo apt-get install docker.io -y
```

📦 **Dependencies**: Already included in the Docker image.

---

## 🧪 Usage

### 1. Run the Docker container

```bash
sudo docker run --gpus all -it --rm -v ${PWD}:/workspace ghcr.io/pip700/gmx:24
```
