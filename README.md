# CVRIE

A Machine Learning project that classifies medical images across 2 tasks:
- **Pneumonia detection** from chest X-ray images
- **Blood cell classification** from microscopy images

3 algorithms are compared on the pneumonia task:
- SVC
- Random Forest
- Logistic Regression

## Setup

**1. Clone Repo**

**2. Create and activate venv**
```bash
python3.12 -m venv .venv
source .venv/bin/activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

## Usage

Open and run the notebook cells.

## Cleanup

**Deactivate and delete venv**
```bash
deactivate
rm -rf .venv/
```