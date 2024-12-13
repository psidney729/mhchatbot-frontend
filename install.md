# Step-be-Step Guide: Setting Up Your Running Environment - MHChatbot

Hello! Let's get started with setting up your Running environment - <b>MHChatbot</b>. We'll go through a series of steps to ensure you have the correct versions of Python and Node.js installed, and then install the necessary dependencies and start your development server.

## Step 1: Check if Python Version is 3.9.x

To check your Python version, open a terminal or command prompt and type:

```bash
python --version
```

This will display the version of Python installed on your system. If you have [![Python 3.9.x](https://img.shields.io/badge/Python-3.9.x-brightgreen)](https://www.python.org/downloads/release/python-390/) installed, you should see a version number like [![Python 3.9.9](https://img.shields.io/badge/Python-3.9.9-brightgreen)](https://www.python.org/downloads/release/python-390/), [![Python 3.9.10](https://img.shields.io/badge/Python-3.9.10-brightgreen)](https://www.python.org/downloads/release/python-390/), etc.

If you don't have [![Python 3.9.x](https://img.shields.io/badge/Python-3.9.x-brightgreen)](https://www.python.org/downloads/release/python-390/) installed, you can download and install it from the official Python website: https://www.python.org/downloads/

## Step 2: Check if Node Version is 18.20.x

To check your Node.js version, open a terminal or command prompt and type:

```bash
node -v
```

This will display the version of Node.js installed on your system. If you have Node.js [![Node.js 18.20.x](https://img.shields.io/badge/Node.js-18.20.x-yellowgreen)](https://nodejs.org/en/download/) installed, you should see a version number like [![Node.js 18.20.4](https://img.shields.io/badge/Node.js-18.20.4-yellowgreen)](https://nodejs.org/en/download/), [![Node.js 18.20.5](https://img.shields.io/badge/Node.js-18.20.5-yellowgreen)](https://nodejs.org/en/download/), etc.

If you don't have Node.js 18.20.x installed, you can download and install it from the official Node.js website: https://nodejs.org/en/download/

## Step 3: npm install

Once you have the correct versions of Python and Node.js installed, navigate to your project directory in the terminal or command prompt. Then, run the following command to install the dependencies listed in your ![package.json](https://img.shields.io/badge/package.json-v18.20.x-blue) file:

```bash
npm install
```

This command may take a few minutes to complete, depending on the number of dependencies listed in your package.json file.

## Step 4: npm run dev or npm run build && npm run start

After the dependencies have been installed, you can start your development server by running the following command:

```bash
npm run dev
```

or

```bash
npm run build && npm run start
```

This command will start your development server, and you should see a message indicating that the server is running.

That's it! You've successfully set up your development environment and started your development server.

### Additional Resources

- Python documentation: https://docs.python.org/3/
- Node.js documentation: https://nodejs.org/en/docs/
- npm documentation: https://docs.npmjs.com/

If you have any issues or questions during these steps, feel free to ask, and I'll do my best to help!
