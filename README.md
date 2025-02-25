# Express.js TypeScript Template

This is a minimal **Express.js + TypeScript** template designed for speed and ease of use. It requires no extra configuration—just install dependencies and start coding!

## 🚀 Features

- **Pre-configured** TypeScript setup
- **Minimal dependencies** for fast setup
- **Nodemon support** for automatic reloads during development
- **Git-ready** with a `.gitignore` to avoid unnecessary files
- No need for an extra package to load environment variables—just create a .env file in the root.

## 📦 Installation

1. **Clone the repository**

   ```sh
   git clone https://github.com/Jonvry/expressjs-ts-template.git
   cd expressjs-ts-template
   ```

2. **Install dependencies**

   ```sh
   npm install
   ```
   
3. **Create a `.env` file in your root directory and define your environment variables:**

   ```sh
   PORT=4000
   ```

4. **Run the development server**

   ```sh
   npm run dev
   ```

5. **Build and start for production**
   ```sh
   npm run build
   npm start
   ```

## 📂 Project Structure

```
express-js-typescript-template/
│── src/
│   ├── index.ts   # Main entry point
│── dist/          # Compiled output (required in development and production)
│── .gitignore     # Ignores unnecessary files
│── package.json   # Project dependencies and scripts
│── tsconfig.json  # TypeScript configuration
```

## 📜 Scripts

| Script          | Description                                     |
| --------------- | ----------------------------------------------- |
| `npm run dev`   | Starts the app in development mode with Nodemon |
| `npm run build` | Compiles TypeScript to JavaScript               |
| `npm start`     | Runs the compiled app                           |

## 📜 Dependencies

- **express** - Web framework for Node.js
- **typescript** - Type definitions for better coding experience
- **nodemon** (dev) - Auto-restarts the server on changes
- **ts-node** (dev) - Run TypeScript directly without compiling

## 💡 Why Use This Template?

- No need for extra configuration.
- Faster development with automatic reloading.
- Pre-configured TypeScript for type safety.

## 🌟 Contributing

Feel free to submit issues and pull requests to improve this template!
