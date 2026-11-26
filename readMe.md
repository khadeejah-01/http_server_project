# Node.js HTTP Server

A basic HTTP server built using **Node.js** and its built-in modules to understand how server-side request handling and URL routing work.

## Features
- Create an HTTP server using Node.js.
- Handle incoming HTTP requests and responses.
- Implement basic routing using the URL pathname.
- Handle query parameters using the URL module.
- Support GET and POST requests for the signup route.
- Log incoming requests with timestamps using the File System module.

## Technologies Used
- Node.js
- JavaScript
- HTTP, File System (`fs`), and URL modules

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/khadeejah-01/http_server_project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd http_server_project
   ```

3. Start the server:
   ```bash
   node index.js
   ```

4. Open `http://localhost:8000` in your browser.

## Available Routes

| Route | Description |
|---|---|
| `/` | Home page |
| `/about?myname=ky` | Returns a personalized greeting |
| `/search?search_query=Java` | Displays search query results |
| `/signup` | Displays signup form message (GET) |

The signup route also handles POST requests.

## Purpose
This project is part of my journey into backend development, exploring how Node.js handles HTTP requests, URL parsing, routing, and server responses.