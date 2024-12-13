
# Files Storage Management Web App

A full-stack file storage management application built with **Next.js** and **Appwrite**, designed to provide users with seamless file management features like uploading, renaming, sharing, and deleting files. The app leverages Appwrite for authentication and database services, ensuring a secure and scalable solution.

## Features

- **Next.js Full-Stack Implementation**: Developed a full-stack storage management app using Next.js. The app integrates server-side rendering (SSR) for optimized performance and is powered by Appwrite for authentication and database services.
  
- **Comprehensive File Management**: Provides advanced file operations:
  - **Uploads**: Leverages Appwrite's storage API to handle file uploads.
  - **Dynamic Routing**: Routes are dynamically generated for file access based on metadata.
  - **File Metadata Management**: Features for renaming, sharing, and deleting files, along with managing metadata.
  
- **Responsive and Scalable Design**: 
  - **Mobile-First UI**: Designed a responsive, mobile-first UI with a clean and intuitive layout.
  - **Dashboard**: A Next.js-powered dashboard for file management and access.
  - **Global Search**: Implements indexed queries for fast and efficient searching.
  - **Sorting and Filtering**: Optimized file sorting and filtering for a seamless user experience.

## Tech Stack

- **Next.js**: A React framework that powers the front-end, offering server-side rendering for enhanced SEO and performance.
- **Appwrite**: A backend server used for authentication, file storage, database management, and real-time updates.
- **Tailwind CSS**: A utility-first CSS framework used for responsive design and UI styling.
- **React**: A JavaScript library used for building interactive and dynamic user interfaces.
  
## Prerequisites

Make sure the following are installed on your machine:

- **Node.js**: [Download Node.js](https://nodejs.org/)
- **Appwrite**: Set up an Appwrite instance (either locally or using Appwrite Cloud).

## Setup Instructions

### 1. Clone the Repository

Clone the repository to your local machine:

git clone https://github.com/Ruthwik25/storage-management.git

2. Install Dependencies
Navigate to the project directory and install the required dependencies:
cd storage-management
npm install

3. Configure Appwrite
Set up an Appwrite account if you haven't already at Appwrite.io.

Create a new project in the Appwrite console and note down the API keys.

Set up your Appwrite configuration in your project:

Create a .env.local file in the root directory.
Add the following environment variables:

NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
NEXT_PUBLIC_APPWRITE_PROJECT_ID=<your-appwrite-project-id>
NEXT_PUBLIC_APPWRITE_API_KEY=<your-appwrite-api-key>

4. Run the Application Locally
Once Appwrite is configured, you can run the app locally:

npm run dev
This will launch the application at http://localhost:3000.

Usage
Sign Up/Log In: Users can sign up or log in to their accounts using Appwrite's authentication system.
File Management:
Upload, rename, and delete files with ease.
Share files with other users via generated links.
Access files through dynamic routing and metadata queries.
Appwrite Setup
Authentication: The app uses Appwrite's authentication system to manage users. Configure the authentication providers (like email/password) in the Appwrite console.
Database: Appwrite’s database is used to store and manage file metadata.
File Storage: The app leverages Appwrite's storage API for file uploads, management, and metadata storage.
Real-Time Updates: Appwrite’s real-time capabilities allow the app to reflect file changes instantly.

Contributing
Fork the repository.
Create a new branch for your feature (git checkout -b feature-name).
Commit your changes (git commit -m 'Add feature').
Push to your branch (git push origin feature-name).
Open a pull request.
