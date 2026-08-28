# Study Organizer

## Overview

Study Organizer is a full-stack web application designed to help students organize their studies in one place. The application allows users to manage modules, study tasks, and personal information while providing a modern and user-friendly interface.

The project was developed to learn the complete software development process, including software architecture, backend development, frontend development, database design, authentication, testing, and deployment.

## Problem

Many students use different applications to organize their studies, such as calendars, note-taking apps, and task managers. This makes it difficult to keep all study-related information in one place.

I wanted to build a single application where students can manage their modules, tasks, and study progress efficiently while learning how professional full-stack applications are designed and developed.

## Solution

Study Organizer provides a centralized platform for managing study-related information. Users can create modules, organize study tasks, manage their profile, and track their academic work in one application.

The system is built as a modern full-stack application with a REST API, secure authentication, a PostgreSQL database, and a responsive frontend. It is designed with a clean architecture to support future extensions such as Moodle integration and a mobile application.

## Architecture

Study Organizer is structured as a full-stack application with a clear separation between frontend, backend, and database.

The backend is built with ASP.NET Core and follows a layered architecture with separate API, Application, Domain, and Infrastructure layers. This keeps business logic separated from technical details such as database access and authentication.

The frontend is implemented with Vue 3 and TypeScript and communicates with the backend through a REST API.

PostgreSQL is used as the relational database, while Entity Framework Core handles data access and database migrations.

Docker is used for the local development environment, and the application is deployed using Vercel, Render, and Neon PostgreSQL.

## Technologies

### Backend
- ASP.NET Core 8
- C#
- Entity Framework Core
- ASP.NET Core Identity
- JWT Authentication
- REST API

### Frontend
- Vue 3
- TypeScript
- Vite
- Pinia
- Vue Router

### Database
- PostgreSQL
- Entity Framework Core Migrations

### Testing
- xUnit
- Vitest
- Playwright

### DevOps & Tools
- Docker
- Git
- GitHub
- GitHub Actions
- Render
- Vercel
- Neon PostgreSQL
- Swagger

## Features

- User registration and login with JWT authentication.
- User profile management.
- Create, update, and delete study modules.
- Create, update, complete, and delete study tasks.
- Dashboard with an overview of modules and tasks.
- Responsive user interface.
- German and English language support.
- Secure access to user-specific data.
- Moodle course import (mock implementation).
- Automated backend, frontend, integration, and end-to-end tests.

## Challenges

During the development of Study Organizer, I faced several technical challenges. One of the biggest challenges was designing a clean and maintainable software architecture that separates business logic from infrastructure and presentation.

Another challenge was implementing secure authentication and authorization using ASP.NET Core Identity and JWT. I also learned how to manage database schema changes with Entity Framework Core migrations and how to deploy a full-stack application using Vercel, Render, and Neon PostgreSQL.

In addition, I focused on writing automated tests, improving code quality, and building a development workflow with Git, GitHub, and Docker.

## What I Learned

Through this project, I gained practical experience in designing and developing a complete full-stack application. I learned how frontend, backend, database, authentication, APIs, testing, and deployment work together in a real software project.

I also improved my understanding of software architecture, clean code, Git workflows, automated testing, and modern development practices. Most importantly, I learned how to analyze technical problems, find solutions, and continuously improve a software product.

## Future Improvements

The project will continue to evolve with new features and improvements. Planned enhancements include a native iOS application, Android support, real Moodle integration, notifications, calendar synchronization, AI-assisted study planning, and additional collaboration features.

The long-term goal is to develop Study Organizer into a complete platform that helps students organize their academic life efficiently.