# Tasks

## Task Management Application

### Overview
This project is a full-stack Task Management Application that uses a Django back-end with MongoDB for data storage, and multiple front-end frameworks (React, Vue, Angular, etc.) to build the UI. Each front-end framework connects to the same back-end API, allowing us to compare how each framework handles various tasks such as state management, API consumption, and UI rendering.

### Key Technologies
- Django: Back-end framework for serving API endpoints and managing business logic.
- MongoDB: NoSQL database used to store task data.
- Django REST Framework (DRF): Used to expose RESTful API endpoints.
- Front-end Frameworks: React, Vue, Angular, etc., each implemented as separate projects that communicate with the same back-end API.

### Project Structure

```
├── backend/               # Django project
│   ├── tasks/             # Django app for task management
│   ├── task_manager/      # Main Django project settings
│   ├── requirements.txt   # Backend dependencies
├── frontend/              # Separate directories for each frontend framework
│   ├── react/             # React front-end project
│   ├── vue/               # Vue.js front-end project
│   ├── angular/           # Angular front-end project
├── README.md              # Project documentation
