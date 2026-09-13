# Smart Queue Tracker

Smart Queue Tracker is a web-based queue management application that I developed using **Python Flask, MongoDB, HTML, CSS, JavaScript, and Bootstrap**. The main goal of the project was to digitize the traditional token-based queue system and make it easier for both customers and staff to manage waiting lines.

### Project Overview

In a traditional queue system, customers often have to wait physically and repeatedly check their turn. To solve this problem, I developed a system where users can generate a **digital token** and track its status and position without continuously standing in the queue.

On the staff side, I created a separate dashboard through which staff members can log in and manage the queue. They can view active tokens, mark tokens as completed, or cancel them when required.

The application stores queue information in **MongoDB**, while **Flask** handles the backend logic, routing, and communication between the frontend and database.

### Key Features

* Users can generate a unique queue token.
* Users can check their current token status and queue position.
* Token status is updated as the queue progresses.
* Staff members have a separate login and management dashboard.
* Staff can mark tokens as **Done** or **Cancelled**.
* Dashboard displays important queue statistics such as:

  * Active tokens
  * Completed tokens
  * Average waiting time
  * Fastest service time
* Queue data is stored persistently in MongoDB.
* Responsive interface developed using Bootstrap, CSS, and JavaScript.
* Added animations and interactive elements to make the interface easier to use.

### Technology Stack

**Frontend:** HTML5, CSS3, JavaScript, Bootstrap, Animate.css
**Backend:** Python, Flask
**Database:** MongoDB

### My Contribution

I worked on the overall development of the application, including the **frontend interface, Flask backend, database integration, token management, staff dashboard, and queue analytics**.

I designed the application flow so that user actions such as generating a token and staff actions such as completing or cancelling a token are reflected in the system and stored in the database.

### Project Structure

```text
SmartQueue/
│
├── app.py
├── requirements.txt
│
├── templates/
│   ├── index.html
│   ├── staff.html
│   └── token.html
│
├── static/
│   ├── background.jpg
│   ├── style.css
│   └── script.js
│
└── README.md
```

### Future Improvements

Some features I would like to add in the future include **SMS/email notifications, multiple service counters, branch-wise queue management, staff performance analytics, and cloud deployment**.

Overall, this project helped me gain practical experience in **Flask backend development, MongoDB database operations, frontend development, authentication, CRUD operations, and connecting different components of a full-stack web application**.
