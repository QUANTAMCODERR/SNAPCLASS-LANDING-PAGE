# SnapClass Frontend

SnapClass is a modern Flask-based landing page for an AI-powered classroom attendance system. The project presents a polished brand experience for a product that uses computer vision, voice recognition, and QR-based enrollment to automate attendance tracking in educational environments.

This frontend is designed to showcase the platform's value to teachers and students, emphasizing convenience, accuracy, and security in classroom management.

---

## Overview

SnapClass is positioned as a next-generation attendance solution for schools and colleges. Instead of relying on traditional manual roll calls, the platform introduces a smart workflow where attendance is managed through:

- AI-based face recognition
- Voice biometric verification
- QR-code driven student enrollment
- Teacher dashboards and student insights
- Digital attendance record management

The landing page is built to communicate these features clearly and professionally, making the product feel credible, modern, and futuristic.

---

## Purpose of the Website

This website acts as the front-facing presentation layer for the SnapClass product. Its role is to:

- Introduce the brand and product vision
- Explain the key benefits of the attendance system
- Showcase the user journey for both teachers and students
- Highlight the technology stack behind the platform
- Drive users to the AI attendance experience via CTA buttons

The website is intentionally designed as a conversion-focused landing page, balancing product communication with a strong visual identity.

---

## Key Sections

### 1. Hero Section
The landing page opens with a bold hero section that communicates the main product message:

- “AI Powered Attendance System”
- A call-to-action encouraging users to start the attendance flow
- Strong visual cards illustrating the platform’s UI
- A polished brand style using dark, white, and purple accent colors

This section is created to immediately capture attention and explain the product’s core value proposition.

### 2. Features Section
The feature area outlines SnapClass’s core capabilities:

- AI Face Analysis
- Sequential Voice ID
- QR-Driven Roster

Each feature card explains how the platform makes attendance faster, more accurate, and less time-consuming for educators.

### 3. Teacher Journey
This section explains the workflow a teacher follows when using the platform:

1. Secure login
2. Interactive dashboard
3. Course management
4. FaceID attendance
5. Voice ID attendance
6. Actionable records

It visually tells the story of how teachers can manage classes and attendance from a single system.

### 4. Student Journey
The student flow is also highlighted to show how learners interact with the product:

1. Instant enrollment
2. Biometric registration
3. Personal dashboard

This helps present the product as a balanced ecosystem that benefits both educators and students.

### 5. Tech Stack Section
The website includes a section showing the core technologies behind the platform, including:

- Streamlit and Flask
- Face recognition technology
- Voice embeddings and audio AI
- Cloud storage and real-time backend services

This gives visitors confidence that the platform is built on modern, scalable technology.

### 6. CTA and Footer
The landing page ends with a conversion-focused section encouraging users to start using the system, followed by a footer with navigation and product information.

---

## Technology Stack

This project uses the following core technologies:

- Python
- Flask
- HTML
- CSS
- Jinja2 templates
- Static asset management for images and styling

The site is lightweight and easy to run locally, making it suitable for demos, frontend previewing, and further product development.

---

## Project Structure

```text
SNAPCLASS-FRONTEND/
├── app.py
├── requirements.txt
├── README.md
├── static/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       └── demo/
└── templates/
    └── index.html
```

### Main files

- `app.py` – Flask application entry point
- `templates/index.html` – main landing page markup
- `static/css/styles.css` – page styling and responsive layout
- `static/img/` – brand and UI images used in the landing page

---

## Run the Project Locally

### 1. Create a virtual environment

```bash
python -m venv venv
```

### 2. Activate the environment

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the Flask app

```bash
python app.py
```

The application will run on:

```text
http://127.0.0.1:5002
```

---

## Development Notes

- The app is configured with `debug=True` in development mode.
- The project is intentionally simple and focused on presentation and marketing.
- It uses Flask’s template engine to render the landing page and static assets efficiently.
- Styling is fully handled in the CSS file, with responsive behavior included for smaller screens.

---

## Features Highlights

- Professional landing page design
- Modern purple and black color palette
- Responsive layout for mobile and desktop devices
- Section-based storytelling for teacher and student workflow
- Clear call-to-action buttons for product engagement
- Strong branding for a futuristic AI classroom product

---

## Future Possibilities

This frontend can be extended in several ways, including:

- Adding a login page
- Building a dashboard interface
- Integrating a real backend API
- Connecting to student and attendance databases
- Adding animations and interactive UI effects
- Expanding the product into a complete SaaS application

---

## Summary

SnapClass Frontend is a clean and modern startup-style landing page for an AI-powered attendance solution. It communicates the product’s vision, demonstrates practical classroom use cases, and presents the project in a way that feels innovative, trustworthy, and ready for real-world deployment.

This project is a strong front-end foundation for a larger educational AI platform and can easily be expanded into a complete application with backend logic, user authentication, and data processing features.
