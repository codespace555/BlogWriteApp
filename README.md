# BlogWrite Web App

Welcome to BlogWrite, a web application for writing and publishing blog posts! This README provides an overview of the BlogWrite web app, its features, and instructions for setting up and running the application locally.

![BlogWrite](https://github.com/codespace555/BlogWriteApp/blob/main/preview/Screenshot%202024-03-13%20015832.png)
## Backend: Appwrite

The backend of BlogWrite is powered by [Appwrite](https://appwrite.io/), an open-source, end-to-end backend as a service (BaaS) solution. With Appwrite, you can easily manage user authentication, database storage, file storage, and more, all from a unified platform.

## Frontend: Vite React

The frontend of BlogWrite is built using [Vite](https://vitejs.dev/guide/), a lightning-fast development environment for building modern web applications using React. With Vite, you can enjoy near-instantaneous hot module reloading, optimized production builds, and a streamlined development experience.

## Getting Started

### Prerequisites:

- Node.js and npm (or yarn) installed on your system. You can check their versions by running `node -v` and `npm -v` (or `yarn -v`) in your terminal. If you don't have them, download and install them from the official websites:
  - [Node.js](https://nodejs.org/en)
  - [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
  - [yarn](https://classic.yarnpkg.com/lang/en/) (optional)

### Clone the Repository:

```
git clone https://github.com/codespace555/BlogWriteApp
```
### Install Dependencies:
```
npm install  # or yarn install
```
This will install all the necessary dependencies for both the frontend and backend.

###Configure Appwrite:
1. Create an Appwrite Project: Sign up for a free Appwrite account at https://appwrite.io/ and create a new project.
2. Set Up Environment Variables: Create a .env file in the root of your project and add the following environment variables, replacing the placeholders with your actual Appwrite project details:

```
VITE_APPWRITE_URL= "Add appwrite url"
VITE_APPWRITE_PROJECT_ID=" add appwrite project id"
VITE_APPWRITE_DATABASE_ID="add databaseid"
VITE_APPWRITE_COLLECTION_ID="add appwrite collection id"
VITE_APPWRITE_BUCKET_ID="add bucket id"
```
You can find your Appwrite endpoint and project ID in your Appwrite project dashboard.



### Run the Development Server:
```
npm run dev  # or yarn dev
```
This will start the development server, typically at http://localhost:5173 (the exact port might vary). Open this URL in your browser to access your blog application in development mode.

## Features
- User authentication and authorization (using Appwrite's built-in features)
- Create, edit, and delete blog posts
- Rich text editing for blog content consider using a library  [TinyMCE](https://www.tiny.cloud/)
- Image uploads for blog posts (using Appwrite's storage capabilities)


## Contributing

We welcome contributions to this project! Feel free to fork the repository, make changes, and submit pull requests.


