# Learning TypeScript
### Setup
  1. Install Node.js and npm on your computer, if they are not already installed.
  2. Create a new project directory and navigate to it using your terminal or command prompt.
  3. Initialize a new npm package by running the following command:
    ```
      npm init -y
    ```

  4. Install the TypeScript compiler as a development dependency by running the following command:
    ```
      npm install typescript --save-dev
    ```

  5. Create a new `tsconfig.json` file in your project directory. This file will contain the configuration settings for the TypeScript compiler. Here's a basic example of what the `tsconfig.json` file could look like:
    ```
      {
        "compilerOptions": {
          "target": "es6",
          "module": "commonjs",
          "sourceMap": true,
          "outDir": "dist"
        },
        "include": [
          "src/**/*"
        ]
      }
    ```

  6. Create a new src directory in your project directory. This directory will contain your TypeScript source files.
  7. Create a new TypeScript file in the src directory and write some TypeScript code in it.
  8. Compile the TypeScript code to JavaScript by running the following command in your terminal:
    ```
      npx tsc
    ```

  9. Your compiled JavaScript files will be generated in the dist directory, as specified in the outDir property of the tsconfig.json file.
  10. You can now run your JavaScript code using Node.js or another JavaScript runtime.