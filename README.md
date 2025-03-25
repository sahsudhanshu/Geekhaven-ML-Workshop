# Geekhaven-ML-Workshop

#  Project Setup Guide  

installation video: https://youtu.be/fDZAizOsmZg?feature=shared

##  Prerequisites  
Before running this project, ensure you have the following installed:  
- **Python (>=3.8)**  
- **pip (Python package manager)**  

## 🛠 Installation Steps  

### 1️⃣ Install Python (If Not Installed)  
Download and install Python from the official website:  
[Python Download](https://www.python.org/downloads/)  

Ensure Python and pip are installed by running:  
```sh
python --version
pip --version
```

### 2️⃣ Create a Virtual Environment (Recommended)  
```sh
python -m venv myenv
source myenv/bin/activate  # For macOS/Linux
myenv\Scripts\activate      # For Windows
```

### 3️⃣ Install Required Dependencies  
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 4️⃣ Verify Installation  
Run the following command to check if all libraries are installed correctly:  
```sh
python -c "import numpy, pandas, matplotlib, seaborn, sklearn; print('All dependencies installed successfully!')"
