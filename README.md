# timetable-generator
# 🗓️ Timetable Generation System (TTGS)

## 📌 Project Description

The **Timetable Generation System (TTGS)** is a Django-based web application that automatically generates optimized class schedules using a **genetic algorithm**. It handles both **hard** and **soft constraints** to produce the most feasible timetable for an academic institution.

The application includes an **authentication and authorization system**. Upon successful login, users are redirected to an **admin dashboard**, where they can manage all necessary data inputs required for timetable generation.

### 🛠️ Admin Dashboard Features
The admin can input:
- 👩‍🏫 Teachers
- 🏫 Classrooms
- ⏰ Timings
- 📘 Courses
- 🏢 Departments
- 🧑‍🎓 Sections

Once all data is populated, the user can head to the **"Generate Timetable"** page and initiate the algorithm. After generation, the timetable can be **downloaded as a PDF**.

---

## 🧰 Technologies Used
- HTML5
- CSS3
- JavaScript
- Python 3.8
- Django 3.0.x
- SQLite3

---

## 🚀 How to Run the Project


  - Clone the Repository
  - Access the project files by using an IDE (PyCharm or Spyder) or via the command line
  - Enter the directory of the main project via the command line or the terminal on the IDE
  - Run the command "python manage.py runserver"
  - Open your browser and access localhost at port http://127.0.0.1:8000/
