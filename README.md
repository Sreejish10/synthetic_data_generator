# synthetic_data_generator
A lightweight Python demo for generating synthetic data using the dspy module, integrating with a local Ollama model and Pydantic for structural realism checks


---

## **Quick Setup Commands**

| Step | Command |
|------|---------|
| Create virtual environment | `python -m venv venv` |
| Activate (Windows) | `venv\Scripts\activate` |
| Activate (macOS/Linux) | `source venv/bin/activate` |
| Upgrade pip | `pip install --upgrade pip` |
| Install IPython kernel | `pip install ipykernel` |
| Add kernel to Jupyter | `python -m ipykernel install --user --name=synthetic --display-name "Python 3.11 (synthetic)"` |
| Install dependencies | `pip install -r requirements.txt` |
| Start Jupyter Notebook | `jupyter notebook` |

---

## **Prerequisites**

Before running the project, ensure you have:

- **Python 3.11+**
- **pip** updated
- **Jupyter Notebook** installed (`pip install notebook`)
- **Optional:** Git, if cloning the repo

---

## **Steps:**

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

# Create a virtual environment named '.syntehtic' soit can be added to .gitignore
python -m venv .syntehtic

# Activate it
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

pip install --upgrade pip
pip install ipykernel

# install all libraries
pip install -r requirements.txt

#Happy Learning
