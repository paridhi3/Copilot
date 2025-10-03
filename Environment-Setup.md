# 🚀 GitHub Copilot Bootcamp: Environment Setup Guide

Welcome to the **GitHub Copilot Bootcamp for Data Engineers**!  
Please complete the following setup steps before **Session 1** to ensure a smooth, hands-on experience.

---

## ✅ Tools You Will Install

| Tool | Purpose |
|------|--------|
| VS Code + Copilot | Main IDE with AI pair-programming |
| Python 3.8+ | For scripting and data engineering tasks |
| Git + GitHub CLI | Version control + GitHub integration |
| Airflow (optional) | Data orchestration |
| dbt CLI | Data quality + testing |
| PostgreSQL (or Snowflake) | Target database |
| Pytest | Unit testing pipelines |
| Terraform (optional) | Infrastructure as Code |
| Docker (optional) | Environment management |

---

## 🧰 1. Install GitHub Copilot in VS Code

### Prerequisites
- GitHub account (with Copilot access)
- [Install VS Code](https://code.visualstudio.com/)

### Steps
1. Open **VS Code**
2. Go to the **Extensions Panel** (`Ctrl+Shift+X`)
3. Search for `GitHub Copilot` → Click **Install**
4. Sign in to your GitHub account when prompted
5. ✅ Test it:
   - Create a file `test.py`
   - Type: `def hello_world():` → Copilot should suggest the full function

---

## 🐍 2. Install Python 3.8 or Higher

### Windows
- Download from: https://www.python.org/downloads/
- ✅ Check **"Add Python to PATH"** during installation

### macOS
```
brew install python
```

### Ubuntu/Debian
```
sudo apt update
sudo apt install python3 python3-pip
```

### Verify
```
python3 --version
pip3 --version
```

## 🐍 3. Create and activate a Virtual Environment

```
python3 -m venv venv        # to create virtual env
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows
```
Then install dependencies (after cloning the repo):
```
pip install -r requirements.txt
```

## 🔁 4. Install Git

### Git
Download from: https://git-scm.com/downloads

