# Assignmnet-week-7-by-Manisha-
This repository contains step-by-step implementations of Week 7 tasks focused on project setup, branch policies, CI/CD pipelines, and security management using Azure DevOps.
This repository contains the implementation of Week 7 tasks using the **Azure DevOps Platform**, covering project setup, branching strategies, CI/CD pipeline management, and security enforcement.

---

## Task Overview

Each task is documented in its own file for clarity. Click the links below to view detailed steps and configurations.

### Task Links

1. [Create a project with user groups and implement group policies](task1.md)

- Created a new project in Azure DevOps.
- Set up multiple user groups:
  - **Project Administrators**
  - **Contributors**
  - **Readers**
- Applied group policies to define access control, visibility, and permission boundaries.

--------------------------------------

2. [Apply branch policies – only admin can access master](task2.md)

- Configured **branch policies** on the `master` branch.
- Only **Project Administrators** have access to `master`.
- **Contributors** are restricted from pushing directly.

----------------------------------------

3. [Apply branch security and locks](task3.md)

- Set branch-level security to enforce:
  - No direct push to `master`.
  - Force pull request-based contributions.
- Applied **branch locks** to prevent accidental updates.

--------------------------------------


4. [Apply branch filters and path filters](task4.md)

- Set **branch filters** to trigger pipeline jobs only on specific branches.
- Used **path filters** to define which file path changes will trigger specific jobs in the pipeline.

--------------------------------------

5. [Create and manage a pull request](task5.md)

- Created a **pull request (PR)** workflow.
- Added reviewers and enabled PR validation builds.
- Ensured code quality checks before merge.

--------------------------------------

6. [Reinforce branch policy and security](task6.md)

- Re-applied and verified policies and security rules on all active branches.
- Confirmed only approved users can modify sensitive branches.

--------------------------------------

7. [Configure triggers in build and release pipelines](task7.md)

- Set **CI triggers** on specific branches to automatically start builds.
- Set **CD triggers** to start releases upon successful build or artifact changes.

--------------------------------------

8. [Apply gates to the pipeline](task8.md)

- Configured **release gates** to:
  - Wait for external approval.
  - Run specific queries or checks before release.
  - Ensure environments are validated before deployment.

--------------------------------------

9. [Restrict contributors to PRs only – no direct merge](task9.md)

- Contributors can **create pull requests**, but:
  - **Cannot merge** into `master` without approval.
  - Required a minimum number of reviewers before PR can be completed.

--------------------------------------


10. [Use work items in pipelines](task10.md)

- Linked **work items** (like tasks/bugs) with commits and pull requests.
- Enabled traceability between code changes and tracked requirements/issues.


--------------------------------------


---
## Tools Used

- **Azure DevOps**  
  For repository hosting, team management, pipeline automation, and branch policy enforcement.

---

## Summary

This task set was aimed at strengthening DevOps practices with:
- Role-based access control
- Pull request workflows
- CI/CD automation
- Safe release gates
- Integration of work tracking with code

Each task demonstrates how to enforce modern DevOps principles using Azure DevOps effectively.

-----------------------

## Author & Credits

**Manisha Shekhawat**  
*Week 7 – Azure DevOps Assignment*

