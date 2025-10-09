# Prescripto - E-Prescription Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/hrisikeshbegin/Prescripto1.svg)](https://github.com/hrisikeshbegin/Prescripto1/stargazers)
[![Forks](https://img.shields.io/github/forks/hrisikeshbegin/Prescripto1.svg)](https://github.com/hrisikeshbegin/Prescripto1/network/members)
[![Issues](https://img.shields.io/github/issues/hrisikeshbegin/Prescripto1.svg)](https://github.com/hrisikeshbegin/Prescripto1/issues)

Prescripto is a full-stack web application designed to streamline the process of creating, managing, and sharing medical prescriptions digitally. It provides a secure and intuitive platform for healthcare professionals to manage patient records and generate e-prescriptions, reducing errors and improving efficiency.

## 📸 Project Screenshot
<p align="center">
  <img src="./frontend/src/assets/sss.png" alt="Prescripto UI" width="900">
</p>


---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🌟 About The Project

This project aims to modernize the traditional prescription process. Doctors can log in to a secure dashboard, manage a database of their patients, and create digital prescriptions that can be easily shared and verified. This eliminates issues like illegible handwriting, lost prescriptions, and manual record-keeping.

---

## ✨ Key Features

- **Secure Doctor Authentication:** JWT-based login and registration for healthcare professionals.
- **Patient Management:** CRUD (Create, Read, Update, Delete) functionality for patient records.
- **E-Prescription Generation:** A dynamic form to create detailed prescriptions including medication, dosage, and instructions.
- **Prescription History:** View and manage all prescriptions issued for each patient.
- **Responsive UI:** A clean and modern user interface built with React.

---

## 🛠️ Tech Stack

This project is built with the MERN stack and other technologies:

* **Frontend:** React, Redux, Axios, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB with Mongoose
* **Authentication:** JSON Web Tokens (JWT), bcrypt.js

---

## 📂 Folder Structure

The repository is organized into two main directories:

Prescripto1/
├── backend/        # Contains all the server-side code (Node.js, Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
└── frontend/       # Contains all the client-side code (React)
├── public/
├── src/
└── package.json


## 🚀 Getting Started

Follow these instructions to get a local copy of the project up and running.

### Prerequisites

Make sure you have the following software installed on your machine:
* **Node.js** (v18.x or later)
* **MongoDB** (or a MongoDB Atlas account)
* **Git**

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/hrisikeshbegin/Prescripto1.git](https://github.com/hrisikeshbegin/Prescripto1.git)
    cd Prescripto1
    ```

2.  **Setup the Backend:**
    ```sh
    cd backend
    npm install
    ```
    Create a `.env` file in the `backend` directory and add the following variables:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
    Start the backend server:
    ```sh
    npm start
    ```

3.  **Setup the Frontend:**
    Open a new terminal window.
    ```sh
    cd frontend
    npm install
    ```
    Start the frontend development server:
    ```sh
    npm start
    ```

---

## 📖 Usage

After installation, the application will be running on `http://localhost:3000`. You can register as a new doctor, log in, add patients, and start creating prescriptions. The backend API will be available at `http://localhost:5000`.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions to improve the project, please fork the repository and create a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/NewFeature`)
3.  Commit your Changes (`git commit -m 'Add some NewFeature'`)
4.  Push to the Branch (`git push origin feature/NewFeature`)
5.  Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 📬 Contact

Hrisikesh Kashyap - [GitHub @hrisikeshbegin](https://github.com/hrisikeshbegin)

Project Link: [https://github.com/hrisikeshbegin/Prescripto1](https://github.com/hrisikeshbegin/Prescripto1)
