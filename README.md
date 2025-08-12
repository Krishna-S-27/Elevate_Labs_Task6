# Portfolio - Task 6

This folder contains the source code for a personal portfolio web application built using **Flask**. The portfolio showcases information about the developer, skills, projects, and provides a contact form for visitors.

---

## Features

- **Home Page:** Displays a centered introduction with the developer's name and a brief description.
- **About Page:** Details the developer's skills, experience, and projects completed during the Elevate Labs internship.
- **Contact Page:** Allows visitors to send a message via a styled contact form.
- **Success Page:** Shows a confirmation message after a successful contact form submission.

---

## How It Works

1. **Flask Application:**  
   The app uses Flask to serve HTML templates and handle routing.
2. **Templates:**  
   All pages are styled with modern CSS for a clean, responsive look.  
   - `index.html`: Home page introduction.
   - `about.html`: Developer profile and project list.
   - `contact.html`: Contact form.
   - `success.html`: Confirmation after form submission.
3. **Contact Form:**  
   The form on the contact page sends a POST request. On successful submission, the user is redirected to the success page.
4. **Static Files:**  
   Custom CSS files are used for consistent styling across all pages.

---

## Application Working Description

This Flask application serves as a personal portfolio website with the following routes:

- **Home (`/`)**: Renders the `index.html` template, displaying a welcome message and introduction.
- **About (`/about`)**: Renders the `about.html` template, showcasing information about the developer, skills, and projects.
- **Contact (`/contact`)**:  
  - On `GET` requests, displays the contact form (`contact.html`).
  - On `POST` requests, receives form data (`name`, `email`, `message`), prints the message to the console, and redirects the

---

## How to Run

1. Install dependencies:
    ```
    pip install flask
    ```
2. Run the Flask app:
    ```
    python app.py
    ```
3. Open your browser and navigate to `http://localhost:5000`

---

## Folder Structure

```
Task_6/
├── app.py
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   └── success.html
├── static/
│   ├── style.css
└── README.md
```

---

## Credits

Developed by **Krishna Shalawadi** as part of the Elevate Labs internship.
