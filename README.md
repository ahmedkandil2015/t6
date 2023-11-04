# Node.js Installation Guide

This guide will walk you through the steps to install Node.js on both Windows and macOS.

## Windows Installation

### 1. Download Node.js:

   - Visit the official Node.js website at https://nodejs.org/
   - Download the LTS (Long Term Support) version for Windows.

### 2. Run the Installer:

   - Double-click the downloaded installer to run it.
   - Follow the on-screen instructions in the installer.

### 3. Verify Installation:

   - Open a Command Prompt or PowerShell window.
   - Type the following commands and ensure you see the version numbers:

     ```shell
     node -v
     npm -v
     ```

## macOS Installation

### 1. Install Homebrew (if not already installed):

   - Open Terminal.
   - Run the following command to install Homebrew:

     ```shell
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```

### 2. Install Node.js using Homebrew:

   - In the same Terminal, run the following command:

     ```shell
     brew install node
     ```

### 3. Verify Installation:

   - In the Terminal, type the following commands to check Node.js and npm versions:

     ```shell
     node -v
     npm -v
     ```

## Creating a New Next.js Project

To create a new Next.js project, follow these steps:

### 1. Open your terminal or command prompt.

### 2. Navigate to the directory where you want to create your Next.js project.

### 3. Run the following command to create a new Next.js project:

   ```shell
   npx create-next-app t6-create-next-app
   ```
   <!-- run project steps -->
   ```shell
   cd t6-create-next-app
   npm run dev
   ```
   <!-- run project steps -->
 


# Your Project Name

## Introduction

Welcome to your Next.js project! This repository is set up with Next.js, a popular React framework, to help you build dynamic and interactive web applications.

## Getting Started

To get started with this project, follow these steps:

1. **Prerequisites:**
   - Make sure you have Node.js and npm installed. You can download and install Node.js from [https://nodejs.org/](https://nodejs.org/).

2. **Initialize the Project:**
   - Open your terminal or command prompt and navigate to the directory where you want to create your Next.js project.
   - Run the following command to initialize a new Next.js project, replacing `your-project-name` with your desired project name:

     ```bash
     npx create-next-app your-project-name
     ```

3. **Navigate to Your Project Directory:**
   - After the initialization is complete, navigate to your project directory using the `cd` command:

     ```bash
     cd your-project-name
     ```

4. **Run the Development Server:**
   - Start the development server by running:

     ```bash
     npm run dev
     ```

   Your Next.js application will be available at `http://localhost:3000` in your web browser.

5. **Folder Structure:**
   - Explore the predefined folder structure of your Next.js project. You'll find directories such as `pages`, `public`, `styles`, and `components`. These are where you'll organize your project.

6. **Start Coding:**
   - Begin building your Next.js application by creating pages, components, and adding your code.

7. **Version Control (Optional):**
   - If you plan to use version control with Git and GitHub, follow these steps:
     - Initialize a new Git repository in your project directory.
     - Create a new GitHub repository to store your project remotely.
     - Add your GitHub repository as the remote.
     - Push your code to GitHub.

## Folder Structure

- `pages`: Define your application's routes and page components.
- `public`: Place static assets like images, fonts, or other files here.
- `styles`: Add your CSS or styling files here.
- `components`: Store common React components used throughout your application.

## Next Steps

Now that you have set up your Next.js project, you can start building your web application with the power of Next.js and React. Check out the Next.js documentation at [https://nextjs.org/docs](https://nextjs.org/docs) for more details on working with the framework and its features.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
