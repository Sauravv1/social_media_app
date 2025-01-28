<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-React_Query-black?style=for-the-badge&logoColor=white&logo=reactquery&color=FF4154" alt="reactquery" />
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
  </div>

  <h3 align="center">A Social Media Application </h3>

</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)

## 🚨 Tutorial

## <a name="introduction">🤖 Introduction</a>

Welcome to my social media application! This platform offers a modern and user-friendly experience with advanced features. The app allows users to create and explore posts, securely authenticate with ease, and interact with content using the latest technologies.

## <a name="tech-stack">⚙️ Tech Stack</a>

- React.js
- Appwrite
- React Query
- TypeScript
- Shadcn
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Authentication System**: I implemented a robust authentication system ensuring user security and privacy.

👉 **Explore Page**: A sleek homepage where users can explore trending posts, with a special section for top creators.

👉 **Like and Save Functionality**: Users can like and save posts, with dedicated pages for managing liked and saved content.

👉 **Detailed Post Page**: A detailed post page providing full content views and recommendations for related posts.

👉 **Profile Page**: Users can view their profile, manage liked posts, and edit personal details.

👉 **Browse Other Users**: A feature that allows users to browse and explore other people's profiles and posts.

👉 **Create Post Page**: Users can create posts with an easy-to-use interface, featuring file management and drag-drop capabilities.

👉 **Edit Post Functionality**: Users can edit their posts anytime, ensuring full control over their content.

👉 **Responsive UI with Bottom Bar**: A responsive design with a bottom navigation bar for smooth mobile interactions.

👉 **React Query Integration**: I’ve used React Query to handle data fetching, enabling auto-caching, parallel queries, and mutations to enhance performance.

👉 **Backend as a Service (BaaS) - Appwrite**: I integrated Appwrite as the backend, providing authentication, storage, database management, and more.

and many more features designed for a seamless user experience!

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Ensure that you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/Sauravv1/social_media_app.git
cd social_media_app

**Installation**

Install the project dependencies using npm:

bash
npm install


**Set Up Environment Variables**

Create a new file named .env in the root of your project and add the following content:

env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=


Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

bash
npm start
