# Bookmark API (Bookmark AP)

## Overview

Bookmark API is a RESTful web service developed using NestJS, TypeScript, Prisma, SQLite, and JWT for authentication. This API allows users to manage bookmarks efficiently by providing endpoints for CRUD (Create, Read, Update, Delete) operations on bookmarks.

## Features

- **Bookmark Module:** Designed and implemented a Bookmark module that enables users to perform CRUD operations on bookmarks.

- **TypeScript:** The project is written in TypeScript, which adds static typing to the codebase, making it more robust and maintainable.

- **Prisma:** Utilized Prisma as the data access layer, offering a type-safe and auto-generated query builder for seamless interaction with the SQLite database.

- **SQLite Database:** The API stores bookmark data in an SQLite database, providing a lightweight and efficient storage solution.

- **JWT Authentication:** Implemented JSON Web Token (JWT) authentication to secure API endpoints and restrict access to authorized users.

## Getting Started

To run the Bookmark API locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mekanhaji/BookmarkAPI.git
   ```

2. **Install Dependencies:**
   ```bash
   cd BookmarkAPI
   npm i
   ```

3. **Configure Database:**
   - Update the Prisma configuration file (`prisma/schema.prisma`) with your database connection details.

4. **Run Migrations:**
   ```bash
   npx prisma migrate dev
   ```

5. **Start the Server:**
   ```bash
   npm run start
   ```

   The API will be accessible at `http://localhost:3333`.

## Authentication

To access the protected endpoints, include the JWT token in the `Authorization` header of your requests.

## Acknowledgments

- NestJS
- Prisma
- SQLite
- TypeScript
- JWT

Feel free to reach out for any questions or issues related to the Bookmark API!