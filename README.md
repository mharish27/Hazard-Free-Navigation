
# Flask Application Setup Guide

This guide provides step-by-step instructions on setting up a Python virtual environment for a Flask application on macOS and Windows, installing necessary dependencies, and running the application.

## Prerequisites

- macOS or Windows operating system 
- Python 3.x installed (Python usually comes pre-installed on macOS) if not download it from [Python Website](https://www.python.org/downloads/)

## Setup on macOS

### Step 1: Clone the code from the git repo using ```git clone```

#### Open Terminal:
- You can find Terminal in the Applications > Utilities folder on macOS.

#### Navigate to Your Project Directory:
- Use `cd` to navigate to your project directory.
- If you haven’t created a directory, use `mkdir project_name` and then navigate into it with `cd project_name`.

#### Create the Virtual Environment:
- Run `python3 -m venv venv` to create a virtual environment named `venv`.

#### Activate the Virtual Environment:
- Activate it by running `source venv/bin/activate`.
- Your command prompt should now indicate that you are inside the virtual environment.

### Step 2: Install Dependencies

With the virtual environment activated, install Flask, OSMnx, NetworkX, Pandas, and scikit-learn.

```bash
pip install Flask osmnx networkx pandas scikit-learn openai
```

## Setup on Windows

### Step 1: Setup a Virtual Environment

#### Open Command Prompt:
- You can search for 'cmd' in the Start menu.

#### Navigate to Your Project Directory:
- Use `cd` to navigate to your project directory.
- If you haven’t created a directory, use `mkdir project_name` and then navigate into it with `cd project_name`.

#### Create the Virtual Environment:
- Run `python -m venv venv` to create a virtual environment named `venv`.

#### Activate the Virtual Environment:
- Activate it by running `venv\Scripts\activate`.
- Your command prompt should now indicate that you are inside the virtual environment.

### Step 2: Install Dependencies

With the virtual environment activated, follow the same command as in macOS:

```bash
pip install Flask osmnx networkx pandas scikit-learn
```

## Step 3: Start the Flask Application

- Run the application with `python app.py`.
- The Flask development server starts, and you can access your app at `http://127.0.0.1:5000/` in a web browser.

## Step 4: Deactivate the Virtual Environment

- When you’re done, deactivate the virtual environment by running `deactivate`.

## Troubleshooting

- Ensure Python 3 is installed correctly.
- Make sure you activate the virtual environment before installing dependencies or running the Flask app.

<h2>Screenshots</h2>

<img width="525" alt="image" src="https://github.com/mharish27/Hazard-Free-Navigation/assets/114908558/f53db5d9-3709-400e-9432-6a4d64c07c6b">

<br />

<img width="296" alt="image" src="https://github.com/mharish27/Hazard-Free-Navigation/assets/114908558/65bfc3c5-352f-4bff-a52b-627aec411f96">

<br />

<img width="295" alt="image" src="https://github.com/mharish27/Hazard-Free-Navigation/assets/114908558/5bc2771d-ce01-4bb9-a067-8339d3c134a3">

<br />

<img width="530" alt="image" src="https://github.com/mharish27/Hazard-Free-Navigation/assets/114908558/7d9178c1-f05e-45a3-a83c-c6ea854ef9c8">




