# fast-uploading
Simple file transfer between devices on the same wifi with increased speed using flask framework.

## 📦 Installation without ```git clone <url>```

### Step 1: Create Project Folder

```bash
# Create folder
mkdir fast-uploading
cd markdown_viewer

# Create subfolders
mkdir templates uploads
```

### Step 2: Create Files

Create these 3 files:

1. **app.py** - Main Flask application 
2. **requirements.txt** - Dependencies 
3. **templates/index.html** - File browser 

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Allow Python through firewall & network protection

How to allow your python application (like a webserver using flask or django):

1. Open **Windows Security** and go to **Firewall & network protection**.
2. Click **"Allow an app through firewall"**.
3. Click **Change settings**, then **"Allow another app..."** and browse to select your ```python.exe``` or ```pythonw.exe``` executable file.
4. Ensure both **Private** and **Public** boxes are checked for the Python entry, depending on your network environment.
   
---

## ▶️ Running the App

```bash
python app.py
```

Output:
```
============================================================
🎨 Modern Markdown Viewer
============================================================
📁 Serving from: C:\Your\Current\Directory
🌐 Open browser: http://localhost:5000
📝 Place your .md files in: C:\Your\Current\Directory
============================================================
...
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://***.***.***.***:5000 (your IP address)
```

Open browser on another devices (on same wifi): **http://<your IP address>:5000**


