# SecAndDevOps

## Project Structure

```
.
├── .github/
│   └── workflows/
│       ├── docker-build.yml
│       └── docker.yml
├── .dockerignore
├── .gitignore
├── app.js
├── app.py
├── Dockerfile
├── package.json
├── requirements.txt
└── README.md
```

## Project Overview

A comprehensive DevOps and Security project implementing containerization, CI/CD pipelines, and application deployment.

## Key Files

- **app.js** - Node.js application
- **app.py** - Python application
- **Dockerfile** - Docker container configuration
- **.github/workflows/** - GitHub Actions CI/CD workflows
- **package.json** - Node.js dependencies
- **requirements.txt** - Python dependencies

## Getting Started

### Prerequisites
- Docker
- Node.js and npm
- Python 3.x

### Installation

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Install Node.js dependencies:
```bash
npm install
```

3. Build Docker image:
```bash
docker build -t secanddevops .
```

## Running the Application

### Python App
```bash
python app.py
```

### Node.js App
```bash
node app.js
```

### Docker
```bash
docker run -p 8080:8080 secanddevops
```

## CI/CD

GitHub Actions workflows are configured in `.github/workflows/` for automated testing and deployment.
