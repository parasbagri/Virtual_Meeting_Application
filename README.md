# Video Chat Application

This repository contains the source code and documentation for a video chat application developed using Node.js, React.js, JavaScript, HTML, and CSS. The application utilizes Socket.io for live streaming and is deployed on Render for the backend and Netlify for the frontend.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)


## Overview

This video chat application allows users to engage in real-time video conversations. It is built using Node.js for the backend, React.js for the frontend, and Socket.io for enabling live streaming communication between users.

## Features

- Real-time video chat
- Simple and intuitive user interface
- Cross-platform (Web and Mobile)

## Prerequisites

Before you begin, ensure you have the following tools installed on your machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/video-chat-app.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd video-chat-app
    ```

3. **Install Backend Dependencies:**

    ```bash
    cd server
    npm install
    ```

4. **Install Frontend Dependencies:**

    ```bash
    cd ../client
    npm install
    ```

## Usage

1. **Start the Backend Server:**

    ```bash
    cd server
    npm start
    ```

    The server will run at `http://localhost:3001`.

2. **Start the Frontend Development Server:**

    ```bash
    cd ../client
    npm start
    ```

    The application will be accessible at `http://localhost:3000`.

3. **Open the Application in Your Browser:**

   Visit `[https://teal-lebkuchen-393350.netlify.app/]` in your browser and start a video chat session.

## Deployment

### Backend Deployment on Render

1. Sign up for a [Render](https://render.com/) account.

2. Create a new web service, and connect it to your GitHub repository.

3. Configure the environment variables on Render, including any secrets or API keys required.

4. Deploy the backend service.
5. [Render](https://meetkare.onrender.com)

### Frontend Deployment on Netlify

1. Sign up for a [Netlify](https://www.netlify.com/) account.

2. Create a new site from Git, and connect it to your GitHub repository.

3. Configure build settings and environment variables on Netlify.

4. Deploy the frontend site.
5. [Netlify](https://teal-lebkuchen-393350.netlify.app/)

## Demo

Check out the live demo of the video chat application:

[Live Demo](https://teal-lebkuchen-393350.netlify.app/)


