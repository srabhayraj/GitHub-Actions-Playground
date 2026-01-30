# GitHub-Actions-Playground
GitHub Action Projects

🚧 Status: In Progress / Learning Phase

## Overview
This project demonstrates a complete CI/CD pipeline built using Jenkins to automate build, test, and deployment processes. The objective was to understand how code changes move from source control to deployment in a controlled and repeatable manner.

## Architecture
Developer pushes code to GitHub → GitHub Actions pipeline triggers → Build and validation steps → Deployment to target environment.

## Tools & Technologies
- GitHub Actions – Pipeline orchestration
- GitHub – Source code management
- Linux – Execution environment
- Shell scripting – Automation logic

## Pipeline Flow
1. Code is pushed to GitHub repository.
2. GitHub Actions detects the change via commit on GitHub.
3. Pipeline executes build steps.
4. Validation steps ensure stability.
5. Application is deployed to the target environment.

## Key Learnings
- Understood CI/CD fundamentals and pipeline stages.
- Learned how GitHub Actions automates repetitive tasks.
- Gained hands-on experience with pipeline failures and troubleshooting.

## Future Enhancements
- Add Docker-based build and deployment
- Integrate automated testing stage
- Migrate pipeline to Jenkins
