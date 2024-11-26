# Bike Store Backend

## Description

Bike Store is a backend web application developed using Node.js, Express, MongoDB, and TypeScript. This project is designed to manage bike-related data through CRUD operations while maintaining a focus on data integrity and efficiency. The application utilizes Mongoose schemas for defining database models and Zod for robust data validation, ensuring secure and consistent data handling.

In addition to CRUD operations, the application supports order processing, where ordering a product adjusts inventory levels and tracks revenue generation. This feature is implemented using two Mongoose models: one for Product and another for Order, demonstrating seamless database relationships and efficient query handling.


## Features

1. **CRUD Operations:** Create, Read, Update, and Delete functionality for managing products and orders.
2. **Inventory Management:** Automatically updates product quantity when an order is placed.
3. **Revenue Tracking:** Tracks revenue generated by product orders.
4. **Zod Validation:** Ensures secure and validated API requests.
5. **TypeScript Integration:** Provides type safety for scalability and maintainability.
6. **Mongoose Models:** Two models for structured database management:
   - **Product Model:** Manages bike-related data.
   - **Order Model:** Handles order placement and updates revenue and product inventory.


## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Technologies Used

1. **Node.js:** Backend runtime environment for handling asynchronous operations.
2. **Express:** Framework for building RESTful APIs.
3. **MongoDB:** NoSQL database for storing product and order data.
4. **Mongoose:** ODM library for schema-based data modeling.
5. **TypeScript:** Type-safe JavaScript for better development experience.
6. **Zod:** Schema declaration and validation library for validating API requests.

## Getting Started

**Prerequisites**

Make sure you have the following installed:

1. **Node.js** (v14 or later).
2. **MongoDB** (local or cloud instance).
3. **npm or yarn**
   

## Installation

1. Clone the repository

> git clone https://github.com/Sha-Hed/bike-store.git

2. Navigate to the project directory:

> cd bike-store

3. Install dependencies:

> npm install

**Environment Variables :**

Create a .env file in the root directory with the following values:
> PORT=5000

> MONGO_URI=mongodb://localhost:27017/bike-store

**Run the Application :**

1. Start the development server:
> npm run start:dev

2. Build the application for production: 
> npm run start:dev


## Features

If your project has a lot of features, list them here.

## 

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Contact

For any inquiries or suggestions, feel free to reach out:

  - **Name:**    Kazi Mohammad Shahed
  - **Email:**   shahedcse14@gmail.com
  - **GitHub:**  Sha-Hed
