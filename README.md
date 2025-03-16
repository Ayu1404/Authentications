# **User-Authentication**

A comprehensive project showcasing various authentication methods in web development. This project demonstrates how to implement secure and modern authentication techniques like OAuth, environment variables, salt hashing, and credential fetching to safeguard user data.

---

## **Features**
- **OAuth Integration**: Securely integrate third-party authentication providers (e.g., Google OAuth).
- **Environment Variables**: Use `.env` files to manage sensitive information securely.
- **Salt Hashing**: Enhance password security with salt and hashing techniques using `bcrypt`.
- **Database Credential Fetching**: Connect to a database securely and retrieve user data.

---

## **Getting Started**

Follow these instructions to run the project locally:

### **Prerequisites**
Make sure you have the following installed:
- Node.js
- PostgreSQL

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Ayu1404/Authentications.git
   cd Authentications
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the `.env` file in the root directory:
   ```plaintext
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   SESSION_SECRET=your_session_secret
   PG_USER=your_database_user
   PG_HOST=your_database_host
   PG_DATABASE=your_database_name
   PG_PASSWORD=your_database_password
   PG_PORT=your_database_port
   ```

4. Start the development server:
   ```bash
   npm start
   ```

---

## **Usage**
- Navigate to `http://localhost:3000` to test the application.
- Use OAuth to log in or register with third-party providers.
- View and interact with the functionality showcasing secure authentication practices.

---

## **Technologies Used**
- **Node.js**: Backend JavaScript runtime.
- **Express.js**: Web framework for handling routes and middleware.
- **bcrypt**: Library for secure password hashing.
- **Passport.js**: Middleware for OAuth and local authentication.
- **PostgreSQL**: Relational database for storing user credentials securely.
- **dotenv**: For managing environment variables.

---

## **Key Concepts**
1. **OAuth**:
   - Enables secure user authentication with providers like Google.
   - Prevents the need to store sensitive passwords.

2. **Environment Variables**:
   - Keeps sensitive data (e.g., database credentials) out of source code.
   - Securely managed via `.env`.

3. **Salt Hashing**:
   - Uses bcrypt to hash passwords with salt, ensuring unique and secure password storage.

4. **Secure Database Connections**:
   - Establishes database connections using credentials safely managed via environment variables.

---

## **Contributing**
Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature/new-feature
   ```
4. Open a pull request.

---

## **License**
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the terms.

---

## **Acknowledgments**
- Inspired by the need for secure authentication in modern web applications.
- Special thanks to the contributors and communities behind `bcrypt`, `passport`, and other libraries used in this project.
