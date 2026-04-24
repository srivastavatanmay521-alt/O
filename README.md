# IDK MAN 
# 🧑‍💻 How to Run This Project in VS Code

## ✅ Step 1: Install Python 3.10
- Download and install Python 3.10

## ✅ Step 2: Open Project in VS Code
1. Open VS Code
2. Click on "File" → "Open Folder"
3. Select your project folder

## ✅ Step 3: Open Terminal
- In VS Code:
  Terminal → New Terminal

## ✅ Step 4: Select Python 3.10
- Press: Ctrl + Shift + P
- Search: "Python: Select Interpreter"
- Choose Python 3.10

## ✅ Step 5: Install Requirements
Run:

pip install -r requirements.txt

⚠️ Make sure file name is:
requirements.txt (spelling must be correct)

## ✅ Step 6: Run the Code

python main.py

---

## ❌ Common Errors

### pip not working
python -m pip install -r requirements.txt

### wrong python version
python --version

(If not 3.10)
python3.10 main.py

### module not found
pip install module_name

---

## 💡 Optional (Recommended)
Create virtual environment:

python -m venv venv

Activate it:
Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

Then install again:
pip install -r requirements.txt
