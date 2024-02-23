# Integrating Pgvector and Langchain for Educational Purposes

Welcome to our educational repository, where we explore the integration of `pgvector` and `langchain` through Jupyter Notebooks for various easy-to-follow scenarios. This project is designed to provide step-by-step instructions and examples for embedding and retrieving data with PostgreSQL and leveraging OpenAI's technologies for educational purposes.

## Structure

This repository is organized into two main folders:

- `data`: This folder contains example input files that are used in the notebooks for embedding into a PostgreSQL database with the `pgvector` extension.
- `notebooks`: This folder contains Jupyter Notebooks that serve as examples for how to integrate `pgvector` with OpenAI's models and `langchain`.

## Example Notebooks

Within the `notebooks` folder, you will find the following examples:

- **pgvector-embedding.ipynb**: Demonstrates the process of using OpenAI's Embedding Models to embed data and store it in a PostgreSQL database using `pgvector`.
- **pgvector-embedding.ipynb**: Demonstrates the process of using Ollama and Nomic Embedding Models to embed data and store it in a PostgreSQL database using `pgvector`.
- **pgvector-client.ipynb**: Shows how to retrieve documents efficiently from a PostgreSQL database using `pgvector`.
- **pgvector-client-openai.ipynb**: An example of how to use a Large Language Model (LLM) to generate content based on vectors and questions, showcasing the integration with `pgvector`.
- **pgvector-client-ollama.ipynb**: Same as above, but with Ollama and Nomic Embed Models.

## Docker Compose Setup

To simplify the setup process, we provide a Docker Compose file that runs a containerized PostgreSQL database with the `pgvector` extension pre-installed. This setup includes an initialization script that prepares the database for vector storage, making it easy to start experimenting with the notebooks provided.

To use the Docker Compose setup, ensure you have Docker and Docker Compose installed on your machine. Then, run the following command from the root of this repository:

```bash
docker-compose up -d
```
