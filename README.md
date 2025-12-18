# Python-Introduction-Smoking-Prevalence



This repository contains the code for our group project for the course "Introduction to Data Analysis with Python".



\## Project Structure:

\- \*\*data\*\*: Contains the raw and cleaned data.

\- \*\*code\*\*: Contains the code, organized by separate notebooks for each task.

\- \*\*output\*\*: Stores the output generated from running the code.

\- \*\*requirements.txt\*\*: Lists the Python packages required for this project.



\## Workflow Guide:



\### 1. \*\*Clone the repository locally\*\*:

Open Git Bash and run the following command to clone the repository:



cd "your\_working\_directory" # Change this to your desired directory

git clone <repository-url> # Replace <repository-url> with the URL from GitHub

cd Python-Introduction-Smoking-Prevalence  # Enter the cloned project folder



\### 2. \*\*Check Git status\*\*:

To check the status of your repository and see if there are any untracked or modified files.

Ideally, do this every time before changing / adding code:



git status



If there are new changes, pull them to you local copy:



git pull



\### 3. \*\*Set up the virtual environment\*\*:

To set up the virtual environment, run the following command in the terminal with cd as the project directory:



python -m venv myenv



This will create a new `myenv` folder in your project directory.



\### 4. \*\*Activate the virtual environment\*\*:

Type in the terminal (VSC terminal or other)



venv\\Scripts\\activate



\### 5. \*\*Install dependencies\*\*:

With the virtual environment activated, install the required Python packages from `requirements.txt`:



pip install -r requirements.txt



This will install all necessary packages.

Remember to update `requirements.txt` when adding new packages by running:

&nbsp; 

pip freeze > requirements.txt



\### 6. \*\*Work on the code\*\*:

You can now start working on the project.



\### 7. \*\*Deactivate the virtual environment\*\*:

When you're done working, deactivate the virtual environment by running:



deactivate



\### 8. \*\*Push your changes to GitHub\*\*:

After making changes to the code, make sure to commit and push them to GitHub in a safe and organized way:



\- \*\*1. Stage the changes\*\*:

&nbsp; git add .



\- \*\*2. Commit the changes\*\* with a message:

&nbsp; git commit -m "Your commit message"



\- \*\*3. Push the changes\*\* to GitHub:

&nbsp; git push origin main

