# React-Django Blog: A Dynamic Multilingual Experience with Dark Mode and Responsive Design

## Overview:

This project showcases a modern and responsive blog page created using React and Django. The blog incorporates key features such as Dark Mode for enhanced readability, ensuring a pleasant user experience across different devices.

## Features:

- Dark Mode: Enjoy a visually comfortable reading experience in low-light environments with the Dark Mode feature.
- Responsive Design: The blog is designed to adapt seamlessly to various screen sizes, providing an optimal viewing experience on desktops, tablets, and mobile devices.
- Multilingual Support: The blog is available in both English and Spanish, offering a user-friendly interface for a diverse audience. Users can effortlessly switch between languages to access content in their preferred language.

## Technologies Used:

- Frontend: React.js
- Backend: Django
- Styling: Tailwind CSS
- Internationalization: i18next for language translation

## Prerequisites

Make sure you have the following tools installed before running the project:

- Python 3.x
- Node.js
- npm (installed automatically with Node.js)

## Project Setup

#### 1. Clone this repository:

```bash
git clone https://github.com/MojeZcg/Blog-Page
cd Blog-Page
```

#### 2. Set up the virtual environment and Python dependencies:

```bash
python -m venv venv
source venv/bin/activate (or "venv\Scripts\activate" on Windows)
pip install -r requirements.txt
```

#### 3. Set up Node.js dependencies:

```bash
npm install
```

#### 4. Set up the build for the django server:

```bash
npm run build
```

## Running the Application

#### Start the Django server with the virtualenv activated:

```bash
python manage.py runserver
```

#### or Start the React development server :

```bash
npm run start
```

The application will be available at http://localhost:8000/ (or "http://localhost:3000/" with React dev Server).

## Environment configuration

1. Copy the `.env.example` file and rename it to `.env`.
2. Fill in the environment variables in the `.env` file as necessary.

## Project Structure

- Backend: Contains the Django code for the API and server configuration.
- Frontend: Contains the React code for the user interface.

## Additional characteristics

### Dark mode

The blog includes a dark theme that activates automatically based on your system settings. If you want to force the dark or light theme, you can do so from the user profile settings.

### Translation

The project supports translation in English and Spanish. You can change the language from the user profile settings. Make sure you add proper translations in the language files.

## Contributions

### If you want to contribute to this project, follow these steps:

#### 1. Create a branch for your feature or bug fix:

```bash
git checkout -b your-branch-name
```

#### 2. Make your changes and commit:

```bash
git add .
git commit -m "Description of your changes"
```

#### 3. Push your changes to the repository:

```bash
git push origin your-branch-name
```

#### 4. Open a pull request on GitHub.

## Contact

For questions or issues, contact me via [Email](https://mail.google.com/mail/u/0/?fs=1&to=jsmonte31@gmail.com&su=Contact+me&tf=cm).

### Thank you for contributing!
