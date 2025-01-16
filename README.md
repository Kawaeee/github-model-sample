# GitHub Model Sample

This project demonstrates how to use the Azure AI Inference service to interact with a language model.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Kawaeee/github-model-sample.git
    cd github-model-sample
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file based on the `.env.example` file and add your GitHub token:
    ```bash
    cp .env.example .env
    # Edit .env to add your GITHUB_TOKEN
    ```
