**EstateElegance**

## Project Overview

Welcome to EstateElegance! This web application is designed to meet the specific needs of the real estate industry. It incorporates modern features and technologies to provide a seamless user experience. This README file will guide you through the installation process, key features, and usage instructions.

### Table of Contents

1. [Installation](#installation)
2. [Key Features](#key-features)
3. [Tech Stack](#tech-stack)
4. [Usage](#usage)
5. [Screenshots](#screenshots)
6. [Contribution](#contribution)

## Installation

To get started with EstateElegance, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/estate-elegance.git
   ```

2. Navigate to the project directory:

   ```bash
   cd estate-elegance
   ```

3. Install dependencies for both the client and server:

   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

4. Configure your MongoDB connection in the `server/.env` file.

5. Run the application:

   ```bash
   cd ../client && npm start
   ```

   Open another terminal:

   ```bash
   cd ../api && npm start
   ```

6. Access the application at `http://localhost:3000` in your browser.

## Key Features

- **User Authentication:**

  - Email and password authentication using JSON Web Tokens (JWT).
  - Seamless Google OAuth integration.
  - Redux Toolkit for streamlined state management.

- **Profile Management:**

  - Users can securely update information and customize profile images.

- **CRUD Operations:**

  - Full control over property listings with MongoDB.
  - Users can create, read, update, and delete listings.
  - Ability to apply discounts and upload up to six images per listing.

- **Listing Pages:**

  - Engaging property pages with image sliders.
  - Simple contact options for potential clients.

- **Advanced Search Functionality:**
  - Modern search options by title, result limitation, and sorting.

## Tech Stack

- React for dynamic interfaces.
- Tailwind CSS for a sleek design.
- Node.js and Express for a robust backend.
- MongoDB for efficient data storage.

## Usage

1. **User Authentication:**

   - Create an account or log in using your Google credentials.

2. **Profile Management:**

   - Update your profile information and customize your profile image.

3. **CRUD Operations:**

   - Create, view, update, and delete property listings.

4. **Listing Pages:**

   - Explore engaging property pages with image sliders.
   - Contact property owners through provided options.

5. **Advanced Search Functionality:**
   - Utilize modern search options to find properties based on title, limitations, and sorting.

## Screenshots

**Login Page**
![Login Page](https://github.com/Emran-Y/mock/raw/main/Screenshots/login.jpg)
**SignUp Page**
![SignUp Page](https://github.com/Emran-Y/mock/blob/main/Screenshots/signUp.jpg)
**Recent Items**
![Recent Items](https://github.com/Emran-Y/mock/blob/main/Screenshots/signUp.jpg)
**Search**
![Search](https://github.com/Emran-Y/mock/blob/main/Screenshots/search.jpg)
**Home Page**
![Home](https://github.com/Emran-Y/mock/blob/main/Screenshots/home.jpg)

## Contribution

We welcome contributions! If you'd like to contribute to the project.

Happy coding!
