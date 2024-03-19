# MERN Stack Dating Web App - College Project

Welcome to the MERN Stack Dating Web App! This project is aimed at providing a comprehensive platform for users to connect and interact with potential matches. It utilizes the MERN stack - MongoDB, Express.js, React.js, and Node.js - to build a robust and scalable web application. 

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone <repository-url>
```

2. Navigate to the server directory:

```bash
cd server
```

3. Edit the environment variables by adding the MongoDB URI in the `.env` file:

```
MONGODB_URI=<your-mongodb-uri>
```

4. Install server dependencies:

```bash
npm install
```

5. Start the backend server:

```bash
npm run start:backend
```

6. Open another terminal window/tab and navigate to the client directory:

```bash
cd ../client
```

7. Install client dependencies:

```bash
npm install
```

8. Start the frontend server:

```bash
npm run start:frontend
```

9. Visit `localhost:8000` in your web browser to access the MERN Stack Dating Web App.

## Features

- User Authentication: Users can sign up, log in, and manage their profiles securely.
- Profile Management: Users can create, edit, and delete their profiles, including adding profile pictures and personal information.
- Matching Algorithm: Implements a matching algorithm to suggest potential matches based on user preferences and interests.
- Messaging System: Allows users to communicate with their matches through a real-time messaging system.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).