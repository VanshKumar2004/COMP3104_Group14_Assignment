# COMP3104_Group14_Assignment

## Group Members
- **Leader:** Vansh Kumar (101420014) - [GitHub](https://github.com/VanshKumar2004)
- **Member 2:** Anthony Aristy (101420011) - [GitHub](https://github.com/AnthonyAristy)
- **Member 3:** Damanpreet Singh (101415046) - [GitHub](https://github.com/damansingh13)
- **Member 4:** Harsh Choudhary (101428605) - [GitHub](https://github.com/Harshlikescoding)

## Project Description
This repository hosts the group assignment for the COMP 3104 DevOps course. The assignment focuses on collaborative Git workflows, branching strategies, and implementing CI/CD using GitHub Actions. The main objectives include demonstrating effective collaboration and setting up automated testing to ensure the quality of code before merging into the main branch.

## Setup Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/VanshKumar2004/COMP3104_Group14_Assignment.git

CI/CD Pipeline
--------------

We have implemented a continuous integration (CI) pipeline using *GitHub Actions*. The pipeline automatically runs builds and tests whenever there is a push or pull request. The configuration file for the CI pipeline is located in .github/workflows/ci.yml.

### CI Pipeline Features:

*   The pipeline is triggered by push and pull request events.
    
*   It performs tests to ensure the code is functioning as expected.
    
*   The CI pipeline helps ensure code quality and reduces integration issues by detecting problems early.
    

Branching Strategy
------------------

We are using a *feature-branch* workflow. Each group member works in their own branch named after their student ID and name (e.g., 101420011-Anthony). When a feature or task is complete, the member creates a pull request to merge the branch into the main branch.

### Workflow:

1.  bashCopy codegit checkout -b
    
2.  Regularly commit changes with meaningful messages.
    
3.  bashCopy codegit push origin
    
4.  Create a pull request to merge your branch into the main branch. Resolve any conflicts before merging.
    
