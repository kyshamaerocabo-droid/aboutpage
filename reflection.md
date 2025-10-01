# Reflection on Environment Setup

Setting up the Django development environment presented several challenges. At first, ensuring the correct Python version was installed and properly linked to the virtual environment required careful checking of system paths. Activating the virtual environment was another step I needed to be precise with, especially in Windows PowerShell, to make sure Django and other dependencies were installed in the venv and not globally.

Installing Django and running the initial `runserver` command helped verify that the environment was correctly configured. Git setup also had its own difficulties, particularly in setting the correct commit user and connecting the local project to the GitHub repository. I learned the importance of checking `git remote -v` and making sure authentication is correct for pushing commits.

Overall, this setup process taught me the value of careful step-by-step configuration and how virtual environments isolate project dependencies. Overcoming these challenges gave me confidence in managing Python projects and using Git efficiently for version control.
