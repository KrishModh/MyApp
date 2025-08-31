# Flask Oracle DB Web App

<img width="2560" height="1440" alt="Screenshot (230)" src="https://github.com/user-attachments/assets/5443ab6b-c119-4be9-8b8c-eebd10f35ae8" />


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
git clone https://github.com/KrishModh/MyApp.git
cd MyApp
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
<img width="2560" height="1440" alt="Screenshot (232)" src="https://github.com/user-attachments/assets/78a6b109-d800-4c79-b6b3-ba825ad655d7" />

### Signup Page
<img width="2560" height="1440" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/b3d2a320-cc3e-40fc-a5ee-d7e0ecc2ff41" />

### User Dashboard
<img width="2560" height="1440" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/3e27d565-f0df-47bf-9fd8-3c1e19650660" />


### Admin Dashboard
<img width="2560" height="1440" alt="Screenshot (234)" src="https://github.com/user-attachments/assets/cd3cb741-eed6-406d-9075-08df4d3c27a2" />


---

## Future Improvements
- Deployment on a live server for global access
- Enhanced admin controls and analytics
- Email verification for user signup

---

## Author
**Krish Modh**  
- GitHub: [Krish Modh](https://github.com/KrishModh)  
- LinkedIn: [Krish Modh](https://www.linkedin.com/in/krish-modh-b38447300)

---

## License
This project is licensed under the MIT License.

