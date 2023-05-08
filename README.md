# Blogzilla - MERN Stack Blog Website

Welcome to Blogzilla, a full-stack blog website built using the MERN (MongoDB, Express.js, React.js, Node.js) stack and styled with Tailwind CSS. This README provides an overview of the project and instructions for setting up the development environment.

## Demo

Check out the [live demo](https://blogzilla.cloud/) of Blogzilla.

## Prerequisites

Make sure you have the following software installed on your system:

- Node.js (v12 or above)
- MongoDB

## Getting Started

To get started with Blogzilla, follow the steps below:

### Client

1. Clone the repository:

   ```
   git clone https://github.com/Sunilthecoder007/blogzilla.git
   ```

2. Navigate to the `client` directory:

   ```
   cd blogzilla/client
   ```

3. Install the dependencies:

   ```
   npm install
   ```

4. Edit `apiPath.js` file:
   
   Open `src/utils/apiPath.js` and modify the `API_PATH` variable to match your server's URL. If you're running the server locally, the default value should work (`http://localhost:5000`).

5. Start the React app:

   ```
   npm start
   ```

   This will launch the client-side of Blogzilla on [http://localhost:3000](http://localhost:3000).

### Server

1. Navigate to the `server` directory:

   ```
   cd blogzilla/server
   ```

2. Install the dependencies:

   ```
   npm install
   ```

3. Edit `.env` file:

   Rename the `.env.example` file to `.env` and edit the configuration values according to your environment. Make sure to set the correct MongoDB connection URL and any other required variables.

4. Start the Node.js server:

   ```
   npm start
   ```

   The server will run on [http://localhost:5000](http://localhost:5000).

Congratulations! You have successfully set up Blogzilla locally. You can now access the blog website by opening [http://localhost:3000](http://localhost:3000) in your web browser.

## Contributing

If you'd like to contribute to Blogzilla, please fork the repository and create a pull request. We welcome your contributions!

## License

This project is licensed under the [MIT License](LICENSE).
