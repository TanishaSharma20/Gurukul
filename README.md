# Gurukul

Gurukul is a classroom management web application built with React. It allows teachers to create classrooms, manage posts, and approve student join requests via OTP. Students can search for classrooms, join them, and view posts.

## Features

- User authentication (login/signup with OTP verification)
- Role-based access (teacher/student)
- Teachers can create classrooms and posts
- Students can search and join classrooms (with OTP approval)
- Profile page showing classrooms created/joined
- Responsive UI with protected routes

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone <your-repo-url>
   cd gurukul
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up environment variables:
   - Edit `.env` and set `REACT_APP_API_BASE_URL` to your backend API URL.

### Running the App

Start the development server:
```sh
npm start
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Running Tests

```sh
npm test
```

### Building for Production

```sh
npm run build
```

## Folder Structure

- `src/` - React source code
  - `components/` - Reusable UI components (Navbar, SearchPopup)
  - `context/` - Auth context provider
  - `pages/` - Main pages (Login, Signup, Profile, Homepage, ClassesDetails)
- `public/` - Static assets and HTML template

## Technologies Used

- React
- React Router
- React Toastify
- Create React App
