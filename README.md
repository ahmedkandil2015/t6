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
 


