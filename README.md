
## Steps to install

1. **Clone the Repository**

    Clone the backend repository from GitHub. 

    ```bash
    git clone [https://github.com/yourusername/blogify-backend.git](https://github.com/tweneboah/mern-blogify-project-course-backend)
    ```

2. **Install the Dependencies**

    Navigate into the cloned project directory and install the necessary packages using npm.
    
    ```bash
    cd blogify-backend
    npm install
    ```

3. **Set Up Environment Variables**

    Create a new file named `.env` in the root directory and set up your environment variables. For example:

    ```bash
    PORT=9080
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

    Replace `your_mongodb_uri` with the connection string to your MongoDB database, and `your_jwt_secret` with a secret string of your choice to be used for signing JSON Web Tokens.

4. **Start the Server**

    Now, you can start the server by running the start script defined in `package.json`.

    ```bash
    npm start
    ```

    The server should start running on http://localhost:5000 or your specified PORT, and connect to the MongoDB database.

