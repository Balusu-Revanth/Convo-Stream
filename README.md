# ConvoStream

ConvoStream is a platform where users can engage in discussions across various subforums. This repository contains both the frontend and backend code for the project.

## Table of Contents

- [ConvoStream](#convostream)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
    - [Frontend Setup](#frontend-setup)
    - [Backend Setup](#backend-setup)
  - [Usage](#usage)

## Features

1. Homepage displays all posts from followed subforums.
2. Search subforums by name or tags.
3. Users can save, upvote, downvote, and comment on posts.
4. Admins can ban certain words from being used in the forum.
5. Offensive posts can be reported for review.
6. Follow users and see a list of followers and following.
7. Create, delete, and request to join subforums.

## Technologies Used

**Frontend:**
- React.js
- Material UI

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

**Authentication:**
- JWT
- bcrypt

## Installation

### Frontend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Balusu-Revanth/Convo-Stream.git
    cd ConvoStream/frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

### Backend Setup

1. Navigate to the backend directory:
    ```bash
    cd ../backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the `backend` directory and add the following configuration variables:
    ```env
    DB=<your_mongodb_uri>
    PORT=<backend_port>
    ```

4. Start the backend server:
    ```bash
    npm start
    ```

## Usage

Once the frontend and backend servers are running, you can access the application at `http://localhost:3000`.
