# QVAC Local AI

A lightweight local AI web application built with Tether's QVAC SDK. Users can enter questions and receive AI-generated responses through a simple web interface while inference runs locally on the computer.

## Repository

**GitHub Repository:** https://github.com/dumang11121/JosephDan

## Features

* Local AI inference
* Simple web interface
* Tether QVAC SDK integration
* On-device AI processing
* No cloud AI API key required
* Node.js and Express application

## QVAC SDK

**Version:** `0.19.1`

The application uses:

* `loadModel()` - Loads the QVAC model
* `completion()` - Generates a response from the user's question

## Requirements

* Node.js 22 or newer
* npm
* A computer supported by QVAC

## Installation

### 1. Open the Repository

[Open JosephDan on GitHub](https://github.com/dumang11121/JosephDan)

### 2. Clone the Repository

Copy and run the following command in your terminal:

`git clone https://github.com/dumang11121/JosephDan.git`

Then enter the project folder:

`cd JosephDan`

### 3. Install Dependencies

`npm install`

## Running the Application

Start the server:

`npm start`

A successful startup should show:

`Loading QVAC model...`

`QVAC model loaded!`

`QVAC app running at http://localhost:3000`

Open the application:

http://localhost:3000

Enter a question and select **Ask AI** to receive a response.

## How It Works

1. The Node.js server starts.
2. `loadModel()` loads the QVAC model.
3. The user enters a question.
4. `completion()` processes the prompt.
5. QVAC generates the response.
6. The response appears in the web interface.

## Project Structure

`JosephDan/`

`public/`

`server.js`

`package.json`

`package-lock.json`

`README.md`

`LICENSE.txt`

`.gitignore`

## Why I Built It

I built this project to explore local AI inference and demonstrate how Tether's QVAC SDK can be integrated into a simple web application.

## Technology

* Node.js
* Express
* Tether QVAC SDK
* JavaScript
* HTML
* CSS

## License

This project is licensed under the MIT License.
