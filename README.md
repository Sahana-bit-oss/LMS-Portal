# NextEdge Learning

NextEdge Learning is a modern Learning Management System (LMS) designed to facilitate seamless educational experiences. The platform is built using Angular for the frontend and Spring Boot for the backend, ensuring a robust and responsive user interface and reliable server-side functionality.

## Features
- **User Management**: Manage students, instructors, and administrators.
- **Course Management**: Create, manage, and enroll in courses with ease.
- **Progress Tracking**: Track learning progress through dashboards and analytics.
- **Interactive Learning**: Integrated quizzes, assignments, and discussion forums.
- **Notifications**: Receive timely updates via email.

## Tech Stack
- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: MySQL
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Monitoring**: Grafana and Prometheus
- **CI/CD**: Jenkins and Argo CD

## Installation

### Prerequisites
1. Install **Node.js** and **npm**.
2. Install **Java 17** or higher.
3. Install **Docker** and **Kubernetes CLI**.
4. Install **Git**.

### Steps
#### Clone the Repository
```bash
git clone https://github.com/Sahana-bit-oss/LMS-Portal.git
cd LMS-Portal
```

#### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Build the project:
   ```bash
   ./mvnw clean install
   ```
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

#### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set environment variables (optional)
 ``` bash
    set NODE_OPTIONS=--openssl-legacy-provider
    $env:NODE_OPTIONS="--openssl-legacy-provider"
 ```
4. Run the application:
   ```bash
   ng serve
   ```

### Docker Deployment
1. Build Docker images:
   ```bash
   docker-compose build
   ```
2. Start the services:
   ```bash
   docker-compose up
   ```

### Kubernetes Deployment
1. Apply Kubernetes manifests:
   ```bash
   kubectl apply -f k8s/
   ```
2. Monitor the deployment:
   ```bash
   kubectl get pods
   ```


## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes and push to the branch.
4. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions or suggestions, feel free to reach out at [GitHub Repository](https://github.com/Sahana-bit-oss/LMS-Portal).
