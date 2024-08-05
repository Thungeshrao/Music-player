# Music-Player-Coding-Ninjas

## Deployment with Docker
1. Build the Docker image:
   ```bash
   docker build -t Music-Player-Coding-Ninjas:v1 .
   ```
2. Run the Docker container:
   ```bash
    docker run -d -p 80:80 Music-Player-Coding-Ninjas:v1
   ```

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request with a description of your changes.
