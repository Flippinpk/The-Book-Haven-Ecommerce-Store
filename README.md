# The Book Haven

**The Book Haven** is a modern, full-stack online bookstore application designed to provide a seamless book browsing and purchasing experience. Built with the MERN stack (MongoDB, Express, React, Node.js) and powered by Vite and Tailwind CSS, it features a responsive user interface, secure backend API, and robust state management.

![Project Banner](https://via.placeholder.com/1200x300?text=The+Book+Haven+Preview)

## Features

*   **Extensive Book Catalog**: Browse a wide collection of books with detailed descriptions and cover images.
*   **Responsive Design**: Fully responsive interface built with Tailwind CSS, ensuring a great experience on mobile, tablet, and desktop.
*   **Modern Frontend**: Developed with React and Vite for lightning-fast performance and hot module replacement.
*   **State Management**: Utilizes Redux Toolkit for efficient global state management across the application.
*   **Secure Backend**: RESTful API powered by Node.js and Express to handle data requests and business logic.
*   **Database Integration**: MongoDB integration using Mongoose for reliable and scalable data storage.
*   **User Alerts**: Interactive notifications using SweetAlert2.

## Tech Stack

### Frontend
*   **React** (v18): Library for building user interfaces.
*   **Vite**: Next Generation Frontend Tooling.
*   **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
*   **Redux Toolkit**: Toolset for efficient Redux development.
*   **React Router**: Declarative routing for React.
*   **SweetAlert2**: Beautiful, responsive, customizable replacements for JavaScript's popup boxes.
*   **Swiper**: Modern mobile touch slider.
*   **React Hook Form**: Performant, flexible and extensible forms with easy validation.

### Backend
*   **Node.js**: JavaScript runtime environment.
*   **Express**: Fast, unopinionated, minimalist web framework for Node.js.
*   **MongoDB**: NoSQL database program.
*   **Mongoose**: Elegant mongodb object modeling for node.js.
*   **Dotenv**: Zero-dependency module that loads environment variables.
*   **Cors**: Package for providing a Connect/Express middleware that can be used to enable CORS.

## Project Structure

```bash
The-Book-Haven/
├── backend/                # Server-side application
│   ├── src/               # Source code for the API
│   ├── index.js           # Entry point for the server
│   ├── package.json       # Backend dependencies and scripts
│   └── .env               # Environment variables (not committed)
├── frontend/               # Client-side application
│   ├── src/               # React source files (components, pages, redux)
│   ├── index.html         # Main HTML file
│   ├── vite.config.js     # Vite configuration
│   ├── tailwind.config.js # Tailwind configuration
│   └── package.json       # Frontend dependencies and scripts
└── README.md               # Project documentation
```

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

*   **Node.js** (v14 or higher) - [Download Node.js](https://nodejs.org/)
*   **npm** (Node Package Manager) - Included with Node.js
*   **MongoDB** - [Download MongoDB](https://www.mongodb.com/try/download/community) or use a cloud database like MongoDB Atlas.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/the-book-haven.git
    cd the-book-haven
    ```

2.  **Setup the Backend:**
    ```bash
    cd backend
    npm install
    ```
    *   Create a `.env` file in the `backend` directory and add your MongoDB connection string and port:
        ```env
        PORT=5000
        DB_URL=mongodb://localhost:27017/book-store-db  # Or your MongoDB Atlas URL
        ```

3.  **Setup the Frontend:**
    ```bash
    cd ../frontend
    npm install
    ```

## Usage

### Running the Backend Server
Navigate to the `backend` directory and start the server:

```bash
cd backend
npm start
# OR for development with auto-restart:
npm run start:dev
```
The server will start on `http://localhost:5000` (or your defined PORT).

### Running the Frontend Application
Open a new terminal, navigate to the `frontend` directory, and start the development server:

```bash
cd frontend
npm run dev
```
Open your browser and navigate to the URL shown in the terminal (usually `http://localhost:5173`).

## Contributing

Contributions are welcome! If you'd like to improve The Book Haven, please follow these steps:

1.  **Fork** the repository.
2.  **Clone** your fork to your local machine.
3.  **Create a new branch** for your feature or bug fix (`git checkout -b feature/amazing-feature`).
4.  **Commit** your changes (`git commit -m 'Add some amazing feature'`).
5.  **Push** to the branch (`git push origin feature/amazing-feature`).
6.  Open a **Pull Request**.
