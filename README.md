# Women's Safety Web App Build for MINOR PROJECT

## Overview
This web application is designed to enhance women's safety by providing a platform where they can seek help in distress situations. The app allows users to send distress signals, report incidents, and provides an admin panel to manage and review incident reports.

### Key Features
- **Distress Signal:** Users can press a button on the homepage to send a distress signal. An email is sent to the user's relatives, parents, and nearby individuals with a map displaying the user's location.

- **Incident Reporting:** Users can report incidents via a form, providing crucial information about the incident.

- **Admin Panel:** Admins can access an admin panel to view and manage all incident reports, including details of distress signals.

- **Media Storage:** Media files, such as images or videos related to incidents, are stored in an AWS S3 bucket for secure and scalable storage.

## Technologies Used
- **MERN Stack:** MongoDB, Express.js, React.js, Node.js for building the web application.

- **AWS S3:** Amazon Simple Storage Service (S3) for storing media files securely.

## Getting Started
Follow these steps to set up and run the project locally:

1. Clone the repository to your local machine:
   ```bash
   https://github.com/Shikhar2106-ctrl/womenSafety1.git
   ```

## Install server dependencies:

```bash
  cd server
  npm install
```

## Install client dependencies:

```bash
  cd ../client
  npm install
```
## Configure the application:

Create a `.env` file in the server directory and configure environment variables such as database connection, email settings.

## Start the development server:

```bash
  cd ./server
  npm start

```
## Start the client:

```bash
  cd ../client
  npm start
```

## Access the application:
Open your web browser and navigate to: `http://localhost:3000`.

## Usage

- Users can register and log in to access the distress signal, incident reporting, and other features.
- Admins can access the admin panel by visiting /admin and log in using admin credentials.
]
