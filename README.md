# MedManage

MedManage is a comprehensive medical management system that integrates a React frontend with a Spring Boot backend. This application allows users to manage patient information, including addresses and personal details, and provides a robust interface for interacting with medical data.

## Features

- **React Frontend**: Interactive and responsive user interface.
- **Spring Boot Backend**: Robust server-side logic with RESTful APIs.
- **Docker Integration**: Containerized deployment for easy setup and scaling.
- **MySQL Server**: Database description here.

## Table of Contents

- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Node.js](https://nodejs.org/) (for the frontend)
- [Maven](https://maven.apache.org/) (for the backend)

### Clone the Repository

```bash
git clone https://github.com/kareemsasa3/MedManage.git
cd MedManage
cd frontend
npm install
cd ..
docker compose build
docker compose up
docker compose down
```

## Contributing

We welcome contributions to MedManage! Please follow these guidelines:

Fork the repository.

Create a feature branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -am 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Inspired by various medical management systems.

Uses Spring Boot for backend development.

Uses React for frontend development.

Docker for containerization.
