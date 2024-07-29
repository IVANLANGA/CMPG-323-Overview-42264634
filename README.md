# CMPG-323-Overview-42264634
Project 1 Repository


Sure, here is the content you can include in your README.md file:

CMPG 323 Overview - <Your Student Number>
Project Repositories
This repository will serve as the main overview repository for the CMPG 323 module. The specific repositories for each project are as follows:

Project 1: Documentation and Planning
Project 2: API Setup
Project 3: Web Application Development
Project 4: Robotic Process Automation (RPA) Testing
Project 5: Reporting and Data Visualization
Documentation
You can access the project documentation here.

Branching Strategy
We will use a simple but effective branching strategy for this project to ensure code quality and smooth collaboration.

main branch: This is the production branch. It should always contain stable and tested code.
develop branch: This branch contains the latest development changes. Features and bug fixes should be merged here once they are completed.
feature branches: For developing new features. They should be named feature/<feature-name>.
bugfix branches: For fixing bugs. They should be named bugfix/<bug-name>.
release branches: For preparing releases. They should be named release/<release-version>.
Workflow
Create a feature or bugfix branch from develop.
Implement your changes and commit them to the feature/bugfix branch.
Once the feature/bugfix is complete, merge it into develop.
After sufficient testing in the develop branch, create a release branch.
Test the release branch thoroughly before merging it into main.
.gitignore File
The .gitignore file is used to specify which files and directories should not be tracked by Git. This helps to avoid committing sensitive information, unnecessary files, and build artifacts.

Common entries in .gitignore:


Storing Credentials and Sensitive Information
It is crucial to keep credentials and sensitive information secure. Here are some practices to follow:

Environment Variables: Use environment variables to store sensitive information. These can be defined in a .env file, which should be added to the .gitignore file to prevent it from being committed.
Configuration Files: Do not store sensitive information directly in configuration files. Instead, reference environment variables in these files.
Secrets Management: Use secrets management tools or services (such as Azure Key Vault, AWS Secrets Manager, etc.) for production environments.
Labels
To organize and prioritize issues, we use the following labels:

Class: For tasks related to class activities.
Project: For tasks related to project work.
Training: For tasks related to training and upskilling.
Other labels: Any additional labels that are relevant to your specific tasks and workflow.
