# JavaScript Internship Projects

This repository contains three independent front-end mini-projects developed using HTML, CSS, and JavaScript. Each project runs fully in the browser without requiring any backend, frameworks, or build tools.

---

## Overview

Included projects:

* **Task List Application (`index.html`)**
* **Professional Digital Clock (`clock.html`)**
* **Personal Portfolio Website (`portfolio.html`)**

All projects are self-contained single-page applications with inline styling and scripting, making them simple to open and run directly.

---

## Features

### Task List Application

A browser-based task manager with interactive behavior.

* Add new tasks
* Edit existing tasks
* Delete tasks with confirmation modal
* Search tasks dynamically
* Persistent storage using `localStorage`
* Modern responsive UI with Font Awesome icons

---

### Professional Digital Clock

A styled digital clock with customization features.

* Real-time clock updates each second
* Toggle between 12-hour and 24-hour formats
* Timezone selection:

  * Local Time
  * UTC
  * New York (EST)
  * London (GMT)
  * Tokyo (JST)
* Clean centered layout using Google Fonts

---

### Portfolio Website

A structured personal portfolio layout suitable for showcasing profile and work.

Sections included:

* About
* Projects
* Skills
* Blog
* Testimonials
* Contact
* Resume
* Certifications

Designed with:

* Responsive layout
* Navigation menu with smooth behavior
* Well-organized structure for easy customization

---

## Technology Stack

* HTML5
* CSS3
* Vanilla JavaScript
* Google Fonts
* Font Awesome (Task List)

No external build systems or frameworks are required.

---

## Project Structure

```
Javascript-internship-main
│
├── index.html       # Task List Application
├── clock.html       # Professional Digital Clock
├── portfolio.html   # Portfolio Website
```

There are no additional folders, assets, or configurations.

---

## Running the Projects

No installation or setup is required.

### Option 1: Open Directly

1. Download the repository
2. Open any of the HTML files in a web browser

### Option 2: Run via Local Server (Optional)

```bash
# Using Python 3
python -m http.server
```

Then open:

```
http://localhost:8000
```

---

## Usage Notes

* All code is inline and can be edited directly in the HTML files.
* The Task List stores data using browser `localStorage`, so tasks persist per browser.
* These are static front-end projects and do not include backend functionality.
* There is no license file included in this repository.
