# ms-didinnuryahya-betest

Backend developer test Node js express js Mysql and Sequilize Orm.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Noderest is a boilerplate Node.js project that incorporates Node.js, Express.js, MySQL, and Sequelize ORM to provide a foundation for API development.

## Features

- Concisely list the key features of your project.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) (Node Package Manager) installed
- Any other specific dependencies...

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dzoxploit/didinnuryahya_betest.git
   cd your-project
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. configure config database in folder config/config.json with your settings databases

4. Run migration

   ```bash
   npx sequelize-cli db:migrate
   ```

5. Run Project

   ```bash
   node server.js
   ```

   default port for this project is :4000

6. For documentation you can import raw in postman and added file noderest.postman_collection.json

### Configuration

configure config database in folder config/config.json with your settings databases this is my example

    ```json
        {

    "development": {
    "username": "root",
    "password": null,
    "database": "db_didinnuryahya_betest",
    "host": "127.0.0.1",
    "dialect": "mysql"
    },
    "test": {
    "username": "root",
    "password": null,
    "database": "db_didinnuryahya_betest",
    "host": "127.0.0.1",
    "dialect": "mysql"
    },
    "production": {
    "username": "root",
    "password": null,
    "database": "db_didinnuryahya_betest",
    "host": "127.0.0.1",
    "dialect": "mysql"
    }
    }

    ```

## API Endpoints

If your project includes a server or API, document the available endpoints, HTTP methods, and request/response examples.

### Auth Routes

- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Log in a user.

### Profile Routes

- `PATCH /api/profile/update`: Update user profile.

### Player Routes

- `POST /api/players/create`: Create a new player.
- `GET /api/players/all`: Get all players.
- `GET /api/players/:id`: Get a player by ID.
- `PUT /api/players/:id`: Update a player by ID.
- `DELETE /api/players/:id`: Delete a player by ID.

## Contributing

If you want to contribute to the project, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md) (create this file if needed).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

Mention any third-party libraries, tools, or resources that you used or were inspired by in your project.
