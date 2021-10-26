# QA BootCamp API Project

## Description

The purpose of this project is to apply all of the techniques and knowledge learned during our API testing sessions to a real backend testing framework.

## Pre-requisites

Web or Desktop version of Postman 9.0.8 or later.

## Test Scenarios

Projects Folder:

- Get All Projects
- Create New Project
- Get Project
- Update Project
- Delete Project

Tasks Folder:

- Get All Tasks
- Create New Project (pre-requisite step)
- Create New Task
- Get Task
- Update Task
- Close Task
- Reopen Task
- Delete Task
- Delete Project (cleanup step)

Negative Projects Scenarios Folder:

- Get All Projects - Invalid authentication token
- Create New Project - Invalid body content
- Get Project - Nonexistent project id
- Update Project - Invalid property sent
- Delete Project - Nonexistent project id

Negative Tasks Scenarios Folder:

- Get All Tasks - Missing authentication header
- Create New Task - Text body format instead of json
- Get Task - Nonexistent task id
- Update Task - Invalid body format
- Close Task - Close an already closed task
- Reopen Task - Invalid authentication header
- Delete Task - Invalid body content sent
