# course-eligible-checker
#  Web Project - Course Recommendation & Credit Tracking System

This project is a web application designed to help students track their academic credits and explore recommended courses based on their curriculum and interests. It leverages Excel-based data for dynamic recommendations and provides an interactive user interface.

---

##  Project Structure

```
Web_project/
├── app.py                   # Main application file
├── blended_courses.py       # Logic for blended course recommendations
├── credit_details.py        # Handles student credit tracking
├── home.py                  # Homepage logic
├── online_courses.py        # Online course recommendation logic
├── data/                    # Excel files used for data processing
├── static/                  # CSS, JS, and image files
├── templates/               # HTML templates
├── requirements.txt         # Python dependencies
├── Procfile.txt             # Deployment file for platforms like Heroku
└── README.md
```

---

##  Features

1. Student Credit Details Tracking  
2. Online Course and Blended Course Recommendations  
3. Excel-based Data Handling for Student Records  
4. Clean and Responsive UI with HTML, CSS, and JavaScript  
5. Flask-Powered Backend Application  

---

##  Tech Stack

- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Data:** Excel Files (.xlsx)  
- **Deployment Ready:** Procfile included for platforms like Heroku  

---

##  Installation & Running Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd Web_project
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app.py
```

### 4. Access the Application  
Visit `http://localhost:5000` in your browser.

---

##  Data Files

The project uses several `.xlsx` files under the `data/` folder for processing student records and recommendations. Make sure these files are present for full functionality.

---



##  Contribution

Contributions, feature suggestions, and bug reports are welcome! Feel free to open an issue or create a pull request.

---

##  License

This project is licensed under the MIT License.

---

##  Acknowledgements

- Developed as part of an academic project.  
- Thanks to [Flask](https://flask.palletsprojects.com/) and open-source community for the tools and resources.  
