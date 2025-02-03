[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/mmanchev23/network/blob/master/LICENSE)

# **Network** - CS50's Project #4

A Twitter-like social network website for making posts and following users. This is **Project #4** from Harvard's CS50 course on **Web Programming with Python and JavaScript**.

## 🚀 Technologies Used

### **Programming Languages**
- HTML5  
  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- CSS3  
  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- JavaScript  
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- Python 3  
  ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)

### **Framework**
- Django  
  ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

### **Database**
- SQLite 3  
  ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)  
- PostgreSQL  
  ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

### **Version Control**
- Git & GitHub  
  ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

### **IDE**
- Visual Studio Code  
  ![VSCode](https://img.shields.io/badge/VisualStudioCode-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## 📌 Getting Started

### **1. Install Python**
Download and install Python from [here](https://www.python.org/downloads/).

### **2. Clone the Repository**
```sh
git clone https://github.com/mmanchev23/network.git
cd network
```

### **3. Set Up a Virtual Environment**
```sh
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### **4. Install Dependencies**
```sh
pip install -r requirements.txt
```

### **5. Apply Migrations**
```sh
python manage.py makemigrations
python manage.py migrate
```

### **6. Run the Development Server**
```sh
python manage.py runserver
```
Access the application at **http://127.0.0.1:8000/**.

## 📂 Project Structure
```
network/          # Main project directory
│── posts/        # Network application directory
│── .gitignore    # Git ignore file
│── LICENSE       # License file
│── manage.py     # Startup file
│── requirements.txt  # Required packages file
```

## 📜 License
This project is licensed under the [MIT License](https://github.com/mmanchev23/network/blob/master/LICENSE).