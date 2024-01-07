# language-identification

# Multilingual Text Identification with CNN

This project utilizes Convolutional Neural Networks (CNN) for the identification of text written in four different languages. The model is trained to classify and distinguish between Tamil, Hindi, Telugu, and kannada languages with high accuracy.

## Technologies Used

- **CNN (Convolutional Neural Network):** The core of the project, CNN is employed to extract features and classify text based on language patterns.

- **Docker:** The project is containerized using Docker, ensuring a consistent and reproducible environment for development and deployment.

- **GitHub Actions for CI/CD:** Continuous Integration and Continuous Deployment (CI/CD) pipelines are set up using GitHub Actions, automating the testing and deployment processes.

- **AWS S3 for Storage:** Amazon S3 is utilized for efficient and scalable storage of datasets and model artifacts.

- **Google Cloud Platform (GCP):** The project is deployed on GCP, taking advantage of its cloud services and infrastructure for scalable and reliable hosting.

## Directory Structure

- **`/src`:** Contains the source code for the CNN model and related scripts.
  
- **`/docker`:** Docker-related files and configurations.

- **`/.github/workflows`:** GitHub Actions workflows for CI/CD.

- **`/data`:** Storage for datasets used in training and testing.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Navigate to the project directory: `cd your-repo`
3. Build the Docker container: `docker build -t your-image-name .`
4. Run the Docker container: `docker run -p 5000:5000 your-image-name`

## CI/CD Pipeline

The CI/CD pipeline is triggered on each push to the main branch. It includes automated testing and, upon successful tests, automatic deployment to the GCP environment.

## Deployment on GCP

The application is deployed on GCP, offering a scalable and reliable environment for serving the language identification model.

## License

This project is licensed under the [MIT License](LICENSE).
