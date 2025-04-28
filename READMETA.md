[README.md](https://github.com/user-attachments/files/19932729/README.md)
# TA Management Application

## 📋 Introduction
The **TA Management Application** is a full-stack platform designed to streamline Teaching Assistant (TA) allocation, approvals, and workload tracking for universities. It supports multiple user roles (Admin, Faculty, TA) with secure, real-time coordination across workflows.

## 🛠️ Technologies Used
- **Backend**: Python, Django, Django REST Framework, SQLite
- **Frontend**: HTML5, CSS3, Bootstrap 4, JavaScript
- **Other**: GCP/AWS Deployment, Salesforce Trailhead (SOQL, Basic Apex)

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ta-management-application.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd ta-management-application
   ```

3. **Create a virtual environment and activate it**
   ```bash
   python -m venv env
   source env/bin/activate  # (Linux/Mac)
   env\Scripts\activate     # (Windows)
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply migrations and start the server**
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

6. Open your browser and visit:
   ```
   http://127.0.0.1:8000/
   ```

## 🌟 Key Features
- Role-Based Access Control (RBAC)
- Real-time TA approval workflow
- Workload tracking for faculty and TAs
- Responsive UI with Bootstrap
- Deployed via GCP/AWS Cloud Services

---

**Note**: Make sure you have Python 3.7+ installed and configured before running the project.

---

### 🌐 Live Demo
*Link to live deployment (optional if deployed)*

