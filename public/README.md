## Host URL: https://65cf01df5da8fe851b3b8b0a--dainty-pothos-7ff0e6.netlify.app/login

# Chat App using MERN Stack

## Frontend Setup

1. Clone the frontend repository:

    ```bash
    git clone https://github.com/Mayureshju/chat-app/tree/main/public
    ```

2. Install node modules:

    ```bash
    cd public
    npm install
    ```

3. Create a `.env` file in the `public` directory and add the following:

    ```env
    REACT_APP_LOCALHOST_KEY="chat-app-current-user"
    ```

4. Update the API URL in your frontend code to point to the backend host.

## Backend Setup

1. Clone the backend repository:

    ```bash
    git clone https://github.com/Mayureshju/chat-app/tree/main/server
    ```

2. Install node modules:

    ```bash
    cd server
    npm install
    ```

3. Create a `.env` file in the `server` directory and add the following:

    ```env
    PORT=your_chosen_port
    MONGO_URL=your_mongodb_url
    ```

4. Update the frontend API configuration to connect to the correct backend host.

## Running the Application

1. Start the backend server:

    ```bash
    cd server
    npm start
    ```

2. Start the frontend application:

    ```bash
    cd public
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` (or your chosen port) to use the chat app.

## Notes

- Ensure MongoDB is running and the connection URL is correctly set in the `.env` file.

Feel free to customize this README further based on additional details or requirements for your specific application.

