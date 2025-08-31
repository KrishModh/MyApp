# Flask Oracle DB Web App

![Project Image](path/to/your-image.png)

## Project Overview
This is a web application built using **Python**, **Flask**, and **Oracle SQL**. The project features a full **user authentication system** with **login** and **signup** functionalities, including separate **admin** and **user** sides. The app is fully **responsive** and runs on **localhost**.

---

## Features

### User Side
- User signup and login
- Dashboard after login
- Responsive design

### Admin Side
- Admin login
- Manage users (view/edit/delete)
- Dashboard with user statistics

### General
- Data stored securely in **Oracle SQL**
- Fully responsive interface for both desktop and mobile
- Flask backend handles all authentication and database operations

---

## Tech Stack
- **Backend:** Python, Flask  
- **Database:** Oracle SQL  
- **Frontend:** HTML, CSS, JavaScript  
- **Server:** Localhost (Flask development server)

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up Oracle SQL database:
- Create the necessary tables using the provided SQL scripts
- Update database credentials in your Flask app

5. Run the Flask application:
```bash
python app.py
```

6. Open your browser and go to:
```
http://127.0.0.1:5000
```

---

## Usage

1. Navigate to the **signup page** to create a new user account.
2. Login using the registered credentials.
3. Admins can login using admin credentials to manage users.
4. After login, users are redirected to their dashboard.

---

## Screenshots
### Login Page
![Login](path/to/login-image.png)

### User Dashboard
![User Dashboard](path/to/user-dashboard.png)

### Admin Dashboard
![Admin Dashboard](path/to/admin-dashboard.png)

---

## Future Improvements
- Deployment on a live server for global access
- Enhanced admin controls and analytics
- Email verification for user signup

---

## Author
**Krish Modh**  
- GitHub: [yourgithubusername](https://github.com/yourgithubusername)  
- LinkedIn: [yourlinkedinprofile](https://www.linkedin.com/in/yourprofile)

---

## License
This project is licensed under the MIT License.

