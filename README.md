## 📄 Documentation
Consultez le [Rapport complet du projet](docs/Rapport_Projet.pdf) ou la [Présentation](docs/PRESENTATION_PROJET_FINAL-PYTHON.pptx) pour plus de détails sur l'architecture et les choix techniques.


# Project Setup

This project uses **Python 3.8+** and manages dependencies with `pip` and `requirements.txt`.

---

## Getting Started

### 1. Clone the Project

```
git clone git@github.com:mohamedMachlou/Jobintech-Ynov-projet-final.git
```

## 2. Installing Dependencies

```
pip install -r requirements.txt
```


## 📝 Collecting User Inputs
### 1. Normal Text Input: 

```python
from utils import input
```

### 2. Single Choice (Radio)

Use this type when the user should **select only one option** from a list.

```python
from utils import radio
```

### 3. Multiple Choice (Checkbox)

Use this type when the user should **select multiple options** from a list.

```python
from utils import checkbox
```

### 4. Select Menu

Use this type for a **menu-style selection**, usually with a longer list or hierarchical options.

```python
from utils import select
```
## 📝 Notes

- Always **activate the virtual environment** before running or installing anything.  
- After installing new packages, **don’t forget to update** `requirements.txt` with:

```
pip freeze > requirements.txt
```


