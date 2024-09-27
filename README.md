# Squiz

**An interactive quiz platform built with HTML, CSS, JavaScript, and Django to enhance learning through customizable quizzes and real-time performance tracking.**

---

## Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Conventions](#conventions)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## About The Project

Squiz is designed to simplify quiz creation, hosting, and participation for educational and entertainment purposes. The platform provides a user-friendly interface for quiz management, real-time scoring, and performance insights, making it ideal for students, educators, and trivia enthusiasts.

---

## Features

- **Custom Quizzes**: Users can create quizzes with multiple formats (MCQs, true/false, short answers).
- **Real-time Scoring**: Instant scoring and feedback for participants.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Secure User Authentication**: Django's built-in authentication system for secure logins.
- **Admin Dashboard**: Django's admin panel for managing quizzes and users.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django (Python)
- **Database**: 
- **Version Control**: Git and GitHub

---

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Make sure you have the following installed:

- **Python 3.x**: [Download here](https://www.python.org/downloads/)
- **Django**: Install using pip
  ```bash
  pip install django
  ```
- **Git**: [Download here](https://git-scm.com)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Prasun-Shiwakoti/Squiz
   ```

2. Navigate to the project directory:

   ```bash
   cd Squiz/Backend
   ```

3. Install the required Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run database migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the Django development server:

   ```bash
   python manage.py runserver
   ```

7. Open your browser and go to:

   ```
   http://127.0.0.1:8000
   ```

---

## Usage

After setting up the project:

- **Create Quizzes**: Navigate to the quiz creation page to design your custom quiz.
- **Host and Participate**: Share quiz links with participants or play quizzes hosted by others.
- **Track Performance**: Get real-time feedback and analyze quiz results.

For more detailed information on how to use Squiz, refer to the in-app documentation or help section.

---

## Conventions

### Code Formatting
- All **JavaScript** code should be formatted with [eslint](https://eslint.org/).
- All **Python** code should follow [PEP-8](https://peps.python.org/pep-0008/) guidelines.

### Naming Conventions
- All variable names should follow **camelCase** or **PascalCase**.

### Commit Message Guidelines
Commit messages should follow the format `<type>: <description>`, where `type` is one of the following:

- **feat**: A new feature.
  - Example: `feat: add user login functionality`
- **fix**: A bug fix.
  - Example: `fix: resolve issue with user profile update`
- **docs**: Documentation-only changes.
  - Example: `docs: update README with installation instructions`
- **style**: Changes that do not affect the meaning of the code (e.g., white-space, formatting).
  - Example: `style: format code according to PEP8 guidelines`
- **refactor**: Code changes that neither fix bugs nor add features.
  - Example: `refactor: reorganize project structure`
- **perf**: Changes that improve performance.
  - Example: `perf: optimize database queries`
- **chore**: Changes to the build process or auxiliary tools and libraries.
  - Example: `chore: update dependencies`

---

## Contributing

We encourage contributions from developers who want to enhance Squiz. To contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

---
