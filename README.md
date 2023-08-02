![Logo](https://res.cloudinary.com/dhnkuonev/image/upload/v1690817781/Frame_1_r2cwtq.png)

# Travel Tales

"[Travel Tales](https://traveltaless.vercel.app)" website, offering an engaging user experience in form of travel stories. At its core, the component renders visually appealing cards that showcase captivating travel posts. Each post includes a title, image, traveler's name, creation date, and tags. Backend part of the project can be found [here](https://github.com/Lucif3r-in/travel-tales-backend)

## Screenshots

![App Screenshot](https://res.cloudinary.com/dhnkuonev/image/upload/v1690807256/Screenshot_2023-07-31_180915_umsw5s.png)

## Tools Used
- body-parser (^1.19.0): This middleware allows you to parse incoming request bodies in a middleware before your handlers, making it easy to access data from HTTP POST requests.

- cors (^2.8.5): CORS is a middleware that enables Cross-Origin Resource Sharing, allowing a server to indicate which origins are allowed to access its resources.

- dotenv (^16.3.1): Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. It's useful for managing sensitive data in development environments.

- express (^4.17.1): Express is a popular and flexible web application framework for Node.js, providing features for building web applications and APIs easily.

- mongoose (^5.9.29): Mongoose is an elegant MongoDB object modeling tool for Node.js. It allows you to define schemas for your data and provides a straightforward way to interact with MongoDB.

- nodemon (^3.0.1): Nodemon is a utility that automatically restarts your Node.js application when changes are detected in your code, making the development process smoother.

- bcryptjs (^2.4.3): Bcryptjs is a library for hashing and salting passwords, providing a secure way to store user passwords in databases.

- jsonwebtoken (^8.5.1): Jsonwebtoken is a library used for generating and verifying JSON Web Tokens (JWTs), which are used for secure transmission of information between parties.

Make sure to include these tools in your project's package.json file and install them using npm or yarn before running your application.

## Run Locally

Clone the project

```bash
  git clone https://github.com/Lucif3r-in/travel-tales-backend
```

Go to the project directory

```bash
  cd travel-tales-backend
```

Install dependencies

```bash
  yarn
```

Start the server

```bash
  yarn start
```

## File Structure

<details>
  <summary>Click to view file structure</summary>
  <pre>
    <code>
📦root
 ┣ 📂controllers
 ┃ ┗ 📜posts.js
 ┃ ┗ 📜user.js
 ┣ 📂middleware
 ┃ ┗ 📜auth.js
 ┣ 📂models
   ┗ 📜tales.js
   ┗ 📜user.js
    </code>
  </pre>
</details>

## Authors

- [@Lucif3r-in](https://github.com/Lucif3r-in)

## Contributing

Contributions are always welcome!

NOTE 1: Please abide by the [Contributing Guidelines](https://github.com/Lucif3r-in/travel-tales-backend/blob/main/CONTRIBUTING.md).

NOTE 2: Please abide by the [Code of Conduct](https://github.com/Lucif3r-in/travel-tales-backend/blob/main/CODE_OF_CONDUCT.md).

NOTE 3: We follow the following [coventional commit types](https://github.com/pvdlg/conventional-commit-types)
