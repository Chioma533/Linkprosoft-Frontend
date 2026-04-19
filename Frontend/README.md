# LinkProSoft Frontend

## Overview

LinkProSoft is a web platform that connects verified professionals with employers seeking specific skills and talent.

This repository contains the **frontend application**, responsible for delivering a responsive, interactive user experience and handling API integration with the backend services.

---

## Features

### Authentication

* User registration and login
* Secure session handling (token-based)
* Role-based access (User, Admin, Super Admin)

### User Experience

* Browse available gigs/jobs
* View professional profiles
* Responsive UI across devices

### Employer Features

* Post and manage gigs
* View applicants and professionals

### Chat System

* Real-time or near real-time messaging interface
* User-to-user and user-to-employer communication

### Admin Dashboard

* Manage users and professionals
* Monitor platform activity
* Content moderation

### Super Admin Dashboard

* Full system control
* Administrative oversight and analytics

---

## Tech Stack

* **Framework:** React
* **Styling:** CSS (Custom / Modular), tailwindcss
* **HTTP Client:** Axios
* **State Management:** Context API
* **Routing:** React Router
* **Build Tool:** Vite

---

## Project Structure

```
src/
│── components/        # Reusable UI components
│── pages/             # Application pages (Login, Dashboard, etc.)
│── context/           # Global state (UserContext, Auth)
│── utils/             # API config, helpers
│── assets/            # Images, icons
│── styles/            # CSS files
```

---

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/linkprosoft-frontend.git

# Navigate into the project
cd linkprosoft-frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## Environment Variables

Create a `.env` file in the root directory:

```
VITE_API_BASE_URL=http://localhost:8000/api
```

---

## API Integration

The frontend communicates with backend services via Axios.

* Token-based authentication (Bearer token)
* Centralized Axios instance
* Request/Response interceptors for:

  * Authorization handling
  * Error handling (401, 500, timeout)

---

## Current Status

* Core UI implemented
* Authentication flow integrated
* Dashboard structure in progress
* API integration ongoing

---

## Future Improvements

* Enhanced real-time chat (WebSockets)
* Performance optimization
* UI/UX refinements
* Improved error handling and loading states

---

## Contribution

This is a personal/project-based frontend implementation.
Contributions, suggestions, and improvements are welcome.

---

