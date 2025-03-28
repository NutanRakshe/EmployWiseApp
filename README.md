# EmployWise React Assignment

## Overview
This is a React-based user management application that integrates with the **Reqres API**. It provides features such as authentication, user listing with pagination, and user editing & deletion.

## Features
### Level 1: Authentication
- Users can log in using the following credentials:
  - **Email:** `eve.holt@reqres.in`
  - **Password:** `cityslicka`
- On successful login, a token is stored, and the user is redirected to the user list page.

### Level 2: List Users with Pagination
- Users are fetched using the **GET /api/users?page=1** endpoint.
- Displays user **ID, Name, Email, and Avatar** in a structured table.
- Implements **pagination** to navigate between user pages.

### Level 3: Edit & Delete Users
- **Edit User:** Users can update **First Name, Last Name, and Email**.
- **Delete User:** Users can be deleted from the list.

## Technologies Used
- **React.js** (Frontend Framework)
- **Bootstrap** (Styling & Responsive UI)
- **Axios** (For API Requests)
- **React Router** (Navigation & Routing)

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/nitesh-scoe/EmployWise.git
   cd EmployWise
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

## Folder Structure
```
EmployWise/
├── src/
│   ├── pages/
│   │   ├── Login.js
│   │   ├── User.js
│   │   ├── EditUser.js
│   ├── style.css
│   ├── App.js
│   ├── index.js
├── public/
├── README.md
├── package.json
```



