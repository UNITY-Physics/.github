# Physics, tools & analysis resources for the UNITY Project

![DevOps](https://github.com/user-attachments/assets/99557d10-0b91-4601-aa53-b4ffbf5f08d1)

# Project Workflow Overview

## 1. Task Initiation

- New task added to the **project board**
- Include:
  - Gear name
  - Assigned developer/collaborators
  - Subtasks
- Tag **@admin** to request creation of the main repo in the organization GitHub

## 2. Repository Setup

- Admin creates the **main GitHub repository** using the FW template

## 3. Development Fork

- Developer forks the repo to their personal GitHub account
- Development is done locally or on a dev server using sample data

## 4. Testing & Pull Request

- Developer tests changes
- When ready, raise a **pull request** to the main repo
- **Minor changes** can be merged directly
- **Major changes** are reviewed in the developer meeting  
  (check documentation and release notes)

## 5. Build & Deployment

- Once approved, merge into the **main branch**
- The main repo builds the updated gear version for Flywheel
- Build can be automated or manually triggered by the FW admin

## 6. Issue Tracking

- Bugs, issues, and feature requests are raised on GitHub
- Once accepted, they are managed within the project workflow
