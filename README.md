Shodh-a-Code: Live Coding Contest Platform

A full-stack, real-time coding contest system that supports instant code evaluation, leaderboards, and asynchronous submission handling.

Overview

Shodh-a-Code allows developers to participate in live coding challenges through a responsive and interactive web interface.
It uses a Spring Boot backend for asynchronous code execution and a Next.js frontend for seamless contest participation.

Key Features
Backend (Spring Boot)

RESTful APIs for contests, problems, submissions, and leaderboard data

Asynchronous code judge engine that executes and evaluates code in real time with resource limits

Entity models include Contest, Problem, TestCase, Submission, and User (implemented using JPA/Hibernate)

Preloaded sample contest with three problems for testing

H2 in-memory database for quick setup and testing

Frontend (Next.js)

Clean and responsive UI for contest and problem display

Code editor with syntax highlighting and auto-resize

Real-time leaderboard updates based on submission results

Integrated submission and result view

Tech Stack

Frontend: Next.js, TypeScript, React Hooks
Backend: Spring Boot, Java, JPA, Hibernate
Database: H2 (for demo), MySQL/PostgreSQL (for production)
Communication: REST APIs

Setup Instructions
Backend

Clone the repository

Navigate to the backend directory

Run using your IDE or execute mvn spring-boot:run

Access APIs at http://localhost:8080

Frontend

Navigate to the frontend directory

Install dependencies using npm install

Start the development server with npm run dev

Open http://localhost:3000 in your browser

Future Improvements

Support for multiple programming languages

Real-time contest management for administrators

Persistent leaderboard and user profiles

Containerized code execution for enhanced security
