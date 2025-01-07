# ArteShop - Strapi Server

## Project Description
This repository contains the Strapi server for the *ArteShop* application. Strapi is used as a CMS (Content Management System) that facilitates the management and delivery of content for the *ArteShop* mobile application, allowing administrators to manage products, categories, users, and more.

## Installation

### Requirements
- Node.js (recommended version: 14.x or 16.x)
- Yarn
- Compatible database (e.g., SQLite, PostgreSQL)

### Installation Steps
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/arte-shop-strapi.git
    ```
2. Navigate to the project directory:
    ```bash
    cd arte-shop-strapi
    ```
3. Install the dependencies:
    ```bash
    yarn install
    ```
4. Configure the environment variables by copying the `.env.example` file and renaming it to `.env`. Then, adjust the values according to your local setup:
    ```bash
    cp .env.example .env
    ```
    **Note:** Make sure to properly configure the database and other critical variables in the `.env` file.

5. Start the Strapi server:
    ```bash
    yarn develop
    ```
    This will start the server in development mode, and you can access the Strapi admin panel at `http://localhost:1337/admin`.

## Usage
The Strapi server is used to:
- Manage dynamic content for the *ArteShop* application.
- Create and manage users and roles.
- Integrate and configure payment options with Stripe.
- Manage shop categories and products.

## Technologies Used
- **Strapi**: CMS used to manage and serve content.
- **Node.js**: Runtime environment.
- **Yarn**: Package manager.
- **Database**: SQLite (default), PostgreSQL, or any other compatible database.

## Contributors
- [Fran](https://github.com/FrankPer-stack)

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
