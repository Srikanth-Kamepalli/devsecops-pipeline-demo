# Setup Instructions

Before running the project locally, ensure the following tools are installed:

1. **Docker**: [Install Docker](https://www.docker.com/products/docker-desktop)
2. **Bandit**: Install with pip install bandit
3. **Trivy**: [Install Trivy](https://github.com/aquasecurity/trivy)

## Step 1: Clone the Repository

Clone the repository to your local machine:

bash
git clone https://github.com/Srikanth-Kamepalli/devsecops-pipeline-demo.git
cd devsecops-pipeline-demo
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt

## Step 2: Install Dependencies
Set up a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt

## Step 3: Build the Docker Image
Build the Docker container:
docker build -t devsecops-demo .

## Step 4: Run the Docker Container
Start the Flask app in the container:
docker run -p 5000:5000 devsecops-demo

Visit http://localhost:5000 to see the app.

