# local-cat
A ready to use 100% local setup for Cat + Ollama + Embedder + Qdrant.  
Forked from [official repo](https://github.com/cheshire-cat-ai/local-cat.git), I just added ngrok support.


# Double command setup
1. docker installation is required (at least docker engine)
2. clone the repo: `git clone https://github.com/giufus/local-cat.git`
3. `cd local-cat`
4. customize `ngrok.yml` according to your details (you need a [ngrok](https://ngrok.com) account)
5. Run the cat: `docker compose up -d`
6. Pull the desired model from ollama library: `docker exec ollama_cat ollama pull <model_name:tags>`


