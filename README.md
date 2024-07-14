<h1> DevOps CICD <h1>
This project implements a CI/CD pipeline for deploying updates to a web application hosted in /var/www/html/devops-cicd. It periodically checks for new commits in the GitHub repository and pulls the latest changes if any new commits are found. After pulling the updates, it reloads Nginx to apply the changes.

<h1> Features <h1>
Automatic Git Pull: The script automatically pulls the latest changes from the GitHub repository if new commits are detected.
Nginx Reload: After pulling the latest changes, the script reloads Nginx to apply the updates.
Periodic Checks: The script continuously monitors the repository for new commits at a regular interval.

<h1> Prerequisites <h1>
Python 3.x: Ensure you have Python 3.x installed.
Nginx: Nginx should be installed and properly configured on your server.
Git: Git should be installed to pull updates from the repository.

<h1> Installation
Clone the Repository: https://github.com/Ram495-ctrl/cicd_testproject.git
