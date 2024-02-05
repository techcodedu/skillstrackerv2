# skillstrackerv2

# Installing Flask Project Dependencies

To set up your Flask project, you'll need to install the packages listed in your `requirements.txt` file. This file contains a list of all the Python packages your project depends on. Follow these steps to install them:

## Prerequisites

- Ensure you have Python installed on your system. Flask supports Python 3.7 and newer.
- It's recommended to use a virtual environment for Python projects to manage dependencies separately for each project.

## Steps

1. **Open your terminal or command prompt.**

2. **Navigate to your project directory:**

    ```bash
    cd path/to/your/project
    ```

    Replace `path/to/your/project` with the actual path to your Flask project directory.

3. **Create a virtual environment (optional but recommended):**

    For Windows:

    ```bash
    python -m venv appvenv
    ```
4. **Activate the virtual environment:**

    On Windows:

    ```bash
    .\appvenv\Scripts\activate
    ```

5. **Install the packages from `requirements.txt`:**

    ```bash
    pip install -r requirements.txt
    ```

  

 # System Features
**Trainer Features:**
1. **Login/Authentication:**
   - Securely log in to the system.

2. **Competency Management:**
   - View a list of all competencies and associated learning outcomes.
   - Add new competencies and learning outcomes if needed.

3. **Progress Updates:**
   - Record student achievements for each learning outcome.
   - Update the status of competencies for individual students.

4. **Reporting:**
   - View graphical reports of individual student progress.
   - View overall progress for all students.

**Student Features:**
1. **Login/Authentication:**
   - Securely log in to view personal progress.

2. **Progress Viewing:**
   - See a graphical representation of personal progress on learning outcomes and competencies.
