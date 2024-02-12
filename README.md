# NestJS Carnival Unveiled

Welcome to the world of NestJS Carnival! This NestJS application awaits your exploration, and here's a comprehensive guide to get you started on this exciting journey.

## Setup Guide

1. **Node.js Installation:**
   - For optimal version management, we recommend the use of `fnm`.

2. **PostgreSQL Installation:**
   1. Set the password for the root `postgres` user (you'll need this later).
   2. Confirm your PostgreSQL installation by entering `psql -U postgres` and providing the password.
   3. Create a database named `carnival` using the command `CREATE DATABASE carnival;`.
   4. If successful, exit the psql shell.

3. **Project Cloning:**
   - Utilize VSCode's built-in git tools for an efficient cloning process. We suggest cloning to `C:/dev/carnival` or a similar location for convenient access.

4. **Dependency Installation:**
   - Open the VSCode terminal at the project root and execute `npm install`.

5. **Configure Environment Variables:**
   - Create a `.env` file following the example in `.env.example` to set up essential environment variables.

6. **Database Initialization:**
   1. Navigate to the project root in the terminal.
   2. Execute `npm run migration:run` to apply migration files.

7. **Congratulations! The project setup is complete. Utilize the commands below to run the app.**

## App Execution Commands

- **Development:**
  ```bash
  npm run start
  ```

- **Watch Mode:**
  ```bash
  npm run start:dev
  ```

- **Production:**
  ```bash
  npm run start:prod
  ```

## Testing Suite

- **Unit Tests:**
  ```bash
  npm run test
  ```

- **End-to-End Tests:**
  ```bash
  npm run test:e2e
  ```

- **Test Coverage:**
  ```bash
  npm run test:cov
  ```

## Database Management

- **Generate Migration Files:**
  ```bash
  npm run migration:generate
  ```

- **Create a New Migration File:**
  ```bash
  npm run migration:create --name=FILE_NAME
  ```

- **Run All Migration Files:**
  ```bash
  npm run migration:run
  ```
