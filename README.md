# File Management System

A simple file management system built with Node.js and Express that allows users to create, view, and manage text files through a web interface.

## Features

- Create new text files
- View list of all files
- Read file contents
- Simple and intuitive web interface

## Prerequisites

- Node.js (v12 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd second
```

2. Install dependencies:
```bash
npm install
```

## Usage

1. Start the server:
```bash
node index.js
```

2. Open your web browser and navigate to:
```
http://localhost:3000
```

## Project Structure

```
├── files/           # Directory for storing text files
├── public/          # Static files (CSS, client-side JS)
├── views/           # EJS templates
├── index.js         # Main application file
└── package.json     # Project dependencies and scripts
```

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript templating)
- File System (fs) module

## API Endpoints

- `GET /` - Display list of all files
- `POST /create` - Create a new text file
- `GET /file/:filename` - View contents of a specific file

## License

ISC

## Author

[Your Name]
