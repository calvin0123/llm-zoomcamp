
# 2. Open-Source LLMs


## 2.7 Ollama - Running LLMs on a CPU (Local)

Docker
```bash
docker run -it \
    -v ollama:/root/.ollama \
    -p 11434:11434 \
    --name ollama \
    ollama/ollama
```

Pulling the model
```bash
docker exec -it ollama bash
ollama pull phi3
```

## 2.8 Ollama & Phi3 + Elastic in Docker-Compose

Creat the Docker compose file with Ollama and Elastic Search

## 2.9 UI for RAG

    * Putting it in Streamlit