# Angular Basics Server

This repository contains the backend server for the Angular Basics project. It serves as the API and data provider for the client-side Angular application located at [Angular Basics Client](https://github.com/diogovlm/angular-basics-client).

## Prerequisites

Before running this project, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en) (LTS version recommended)
- [npm](https://www.npmjs.com) (comes with Node.js)

## Getting Started

Follow these steps to set up and run the server locally:

### 1. Clone the repository:

```bash
git clone https://github.com/diogovlm/angular-basics-server.git
```

### 2. Navigate into the project directory:

```bash
cd angular-basics-server
```

### 3. Install dependencies:

```bash
npm install
```

### 4. Start the server:

```bash
node server.js
```

This will start the server on http://localhost:3000/ (or the port specified in the project configuration).

## Configuration

- The default port for the server is 3000. If you want to change the port, modify the configuration in both server and client project settings.
- Ensure that the server is running before starting the client-side application from the [Angular Basics Client](https://github.com/diogovlm/angular-basics-client) repository.

## Usage
Once the server is running, it will handle API requests and serve data to the Angular client. Make sure you have cloned and set up the client repository by following the instructions in the [Angular Basics Client](https://github.com/diogovlm/angular-basics-client) README file.
