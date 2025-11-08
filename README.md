# GitHub Actions Lab 1

## ⚙️ CI Workflow

This repository includes a **GitHub Actions** workflow for basic Continuous Integration.

### 🔁 Trigger
Runs automatically on every **push** to the repository.

### 🧩 Steps
1. **Set up Python 3.11**  
   Uses `actions/setup-python@v5` to configure Python.

2. **Install dependencies**  
   Installs packages from `requirements.txt` using pip.

### 📁 File
`.github/workflows/ci.yml`

