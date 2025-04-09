# 🃏 Random Jokes API

This project is a simple RESTful API built with Node.js and Express.js that serves random programmer jokes. Every time a client makes a GET request to the `/api/joke/random` endpoint, the server returns one random joke in JSON format from a predefined jokes array.

---

## 🚀 Project Overview

**Objective:**  
The aim of this project is to deepen your backend development skills by:
- Creating an Express server
- Defining and managing RESTful API routes
- Returning dynamic text data (jokes) in JSON format
- Deploying the API to Render for public access

**Live Demo:**  
Access the live API here:  
[https://randomjoke-api.onrender.com/api/joke/random](https://randomjoke-api.onrender.com/api/joke/random)

---

## ⚙️ Setup and Installation

Follow these steps to run the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/random-jokes-api.git
   cd random-jokes-api
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Server:**
   ```bash
   node index.js
   ```
   The API will run on `http://localhost:6070`.

---

## 🔗 API Endpoints

### 1. Home Route

- **GET /**  
  Returns a simple welcome message.
  
  **Example Request:**
  ```
  http://localhost:6070/
  ```
  **Response:**
  ```
  Welcome to Random Jokes Api!
  ```

### 2. Random Joke Route

- **GET /api/joke/random**  
  Returns one random joke from a predefined array in JSON format.
  
  **Example Request:**
  ```
  http://localhost:6070/api/joke/random
  ```
  
  **Example Response:**
  ```json
  {
    "joke": "Guess the number of programmers it takes to change a light bulb? Zero its a hardware problem"
  }
  ```

---

## 🧱 Code Overview

Your `index.js` file contains the main code that:
- Sets up the Express server on port 6070.
- Declares a predefined array of programmer jokes.
- Implements two routes:  
  - The Home route ("/") for a welcome message.
  - The `/api/joke/random` route that randomly selects one joke and returns it as JSON.
---

## 🧪 Testing the API

You can test the API endpoints using any REST client such as **Postman** or your web browser:

- **Home Route:**  
  Visit: `http://localhost:6070/`  
  You will see the welcome message.

- **Random Joke Route:**  
  Send a GET request to: `http://localhost:6070/api/joke/random`  
  You should receive a JSON response with a random joke.

---

## 💡 Challenges and Learnings

- **Random Data Selection:**  
  Implementing random selection from an array using JavaScript’s `Math.random()` and `Math.floor()`.

- **Route Handling:**  
  Designing clear API endpoints in Express.js.

- **Error Handling:**  
  Managing exceptions to provide meaningful error messages in case of failures.

- **Deployment:**  
  Deploying the API on Render to make it publicly accessible.

---

## 🌍 Deployment

This project is deployed on [Render](https://render.com/).  
Every code update pushed to the main branch triggers an auto-deployment on Render.  
Access the live API here:  
[https://randomjoke-api.onrender.com/api/joke/random](https://randomjoke-api.onrender.com/api/joke/random)

---

## ✅ Assignment Checklist

- [x] Created a Node.js project with Express.
- [x] Implemented the `/api/joke/random` route using a predefined jokes array.
- [x] Tested the API endpoints using Postman.
- [x] Deployed the API on Render.
- [x] Documented the project with this README.

---

## 📚 License(ISC)

This project is for educational purposes only.  
Feel free to fork and modify it to enhance your learning.

---

## ✨ Author

Made with ❤️ by [Priya Maity](https://github.com/PriyaMaity)
```
