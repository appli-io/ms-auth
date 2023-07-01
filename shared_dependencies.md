Shared Dependencies:

1. NestJS: The main framework used for building the server-side application. It's used across all the .ts files.

2. PassportJS: Used for handling authentication in the auth module. It's used in the auth.service.ts and all strategy files.

3. JWT: Used for token-based authentication. It's used in the auth module and user module.

4. TypeORM: Used for interacting with the PostgreSQL database. It's used in the user module and database module.

5. PostgreSQL: The database used in the application. It's used in the database module and user module.

6. OAuth2 and OpenID Connect: Used for integrating authentication with Microsoft, Google, and email/password. It's used in the auth module.

7. Docker: Used for containerizing the application. It's used in the main.dockerfile.

8. Kubernetes: Used for managing the deployment and operation of the containers. It's used in all the .yaml files in the k8s directory.

9. RabbitMQ or Apache Kafka: Used for handling asynchronous and distributed communication between microservices. It's used in the app module and potentially in other modules.

10. Kong or Traefik: Used for managing routing and authentication of requests to the microservices. It's used in the API Gateway deployment.

11. Jenkins, GitLab CI/CD, GitHub Actions: Used for automating the build, test, and deployment of the application. They are used in the respective files in the ci-cd directory.

12. Constants: Used across multiple files for maintaining consistency.

13. User Entity: Used in the user module and auth module for handling user data.

14. Database Providers: Used in the database module and potentially in other modules for providing database connection.

15. Environment Variables: Used across multiple files for configuration purposes. They are defined in .env and .env.example files.

16. ORM Config: Used for configuring TypeORM. It's defined in ormconfig.json.

17. Ingress Router: Used in the API Gateway for handling incoming requests and routing them to the appropriate microservice. It's used in the API Gateway deployment.