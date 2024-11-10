# StoreIt - Storage Management System

![Build & Deploy](https://img.shields.io/badge/Build%20&%20Deploy-Storage%20Platform-FF6B6B)

<div align="center">
  <img src="![image](https://github.com/user-attachments/assets/a9a33cd5-bee4-46c1-a59d-73bb0b5c7af8)"
 alt="StoreIt Banner" width="100%" />
  <br />
  <div>
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/Appwrite-F02E65?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
  </div>
  <h3 align="center">Storage and File Sharing Platform</h3>
</div>

## 📋 Table of Contents
- [🤖 Introduction](#introduction)
- [⚙️ Tech Stack](#tech-stack)
- [🔋 Features](#features)
- [🤸 Quick Start](#quick-start)
- [👥 Contributing](#contributing)

## 🤖 Introduction
A storage management and file sharing platform that lets users effortlessly upload, organize, and share files. Built with the latest Next.js 15 and the Appwrite Node SDK, utilizing advanced features for seamless file management.


## ⚙️ Tech Stack
* React 19
* Next.js 15
* Appwrite
* TailwindCSS
* ShadCN
* TypeScript

## 🔋 Features
* **User Authentication with Appwrite:** Implement signup, login, and logout functionality using Appwrite's authentication system
* **File Uploads:** Effortlessly upload a variety of file types, including documents, images, videos, and audio
* **View and Manage Files:** Browse through uploaded files stored in Appwrite storage, view on a new tab, rename file or delete
* **Download Files:** Users can download their uploaded files giving them instant access to essential documents
* **File Sharing:** Users can easily share their uploaded files with others, enabling collaboration
* **Dashboard:** Gain insights with a dynamic dashboard showing total and consumed storage, recent uploads, and file type summaries
* **Global Search:** Quickly find files and shared content across the platform
* **Sorting Options:** Organize files efficiently by sorting them by date, name, or size
* **Modern Responsive Design:** Fresh and minimalist UI that emphasizes usability across all devices

## 🤸 Quick Start

### Prerequisites
Make sure you have the following installed on your machine:
* Git
* Node.js
* npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/BinaryBrain45/storeIt.git
cd storeIt
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create a new file named `.env.local` in the root of your project and add the following content:

```bash
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the Appwrite website.

### Running the Project
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 👥 Contributing

We welcome contributions to improve this project! Here's how you can help:

1. Fork the repository
2. Create a new branch for your feature:
```bash
git checkout -b feature/your-feature-name
```

3. Make your changes and commit them:
```bash
git commit -m "Add some feature"
```

4. Push to your branch:
```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request

### Guidelines
- Follow the existing code style and formatting
- Write clear, descriptive commit messages
- Add tests for new features when possible
- Update documentation as needed
- Make sure your PR description clearly describes the changes you're proposing

### Bug Reports
Found a bug? Please open an issue with:
- A clear title and description
- As much relevant information as possible
- A code sample or an executable test case demonstrating the issue

### Feature Requests
Have ideas for new features? Open an issue to describe:
- The feature you'd like to see
- Why you need it
- How it should work

