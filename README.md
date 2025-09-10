# Streamscape
Streamscape is a complete web application that lets users browse, watch, and discover movies. It's built with the **MERN** stack:

-   **MongoDB**: A NoSQL database for flexible data storage.
-   **Express.js**: A back-end web application framework for Node.js.
-   **React**: A JavaScript library for building the user interface.
-   **Node.js**: A server-side JavaScript runtime environment.

## Getting Started

To run Streamscape locally, you need to have **Node.js** installed.

### Installation

1.  **Clone the repository:**

2.  **Set up environment variables:**

    Create a `.env` file in each of the following folders: `backend API`, `frontend user`, and `frontend admin`. This file will store your essential configuration details.

    * **MongoDB:** Get your connection string from a new or existing MongoDB database.
    * **Firebase:** Set up a Firebase project and get the connection string.

3.  **Install dependencies and start the servers:**

    You'll need to run `npm install` and `npm start` in three separate terminals for each part of the application.

    **Backend API**
    ```bash
    cd backend API
    npm install
    npm start
    ```

    **Frontend User**
    ```bash
    cd frontend user
    npm install
    npm start
    ```

    **Frontend Admin**
    ```bash
    cd frontend admin
    npm install
    npm start
    ```

---

## Screenshots

Explore the different views of the Streamscape application.

### User Pages

| <img src="screenshots/User%20pages/4.Home%20page.png" alt="Home page" width="200"/> | <img src="screenshots/User%20pages/5.Movies%20page.png" alt="Movies page" width="200"/> | <img src="screenshots/User%20pages/6.Blog%20page.png" alt="Blog page" width="200"/> |
|:---:|:---:|:---:|
| **Home** | **Movies** | **Blog** |

| <img src="screenshots/User%20pages/7.Team%20page.png" alt="Team page" width="200"/> | <img src="screenshots/User%20pages/8.Contact%20us%20page.png" alt="Contact us page" width="200"/> | <img src="screenshots/User%20pages/9.View%20profile.png" alt="View profile" width="200"/> |
|:---:|:---:|:---:|
| **Team** | **Contact** | **Profile** |

### Admin Panel

| <img src="screenshots/Admin%20pages/1.Dashboard.png" alt="Admin Dashboard" width="200"/> | <img src="screenshots/Admin%20pages/2.Users%20list.png" alt="Users list" width="200"/> | <img src="screenshots/Admin%20pages/3.Movies%20list.png" alt="Movies list" width="200"/> |
|:---:|:---:|:---:|
| **Dashboard** | **Users** | **Movies** |

---

## Database Schema

<div align="center">
  <img src="screenshots/Database%20structure/1.Structure%20of%20database.png" alt="Database structure diagram" />
</div>

---

## Acknowledgments

This project was developed by following the comprehensive **"React Node.js Netflix App | MERN Stack + JWT Full Tutorial"** by **Lama Dev** on YouTube. The tutorial was an excellent guide for understanding and implementing the MERN stack to create a dynamic and engaging streaming platform. I am grateful for the detailed explanations and insights provided, which were essential to completing this project.