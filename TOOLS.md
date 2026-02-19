### SSH

- linux-server → 192.168.1.247, port 6905, user: sd22750

### Server Hardware (linux-server)

| Resource | Specs |
|----------|-------|
| **CPU** | Intel Core i5-3470 @ 3.20GHz (4 cores, 4 threads) |
| **RAM** | 31 GB (6.2 GB used / 20%) |
| **Root Disk** | 1.8 TB (484 GB used / 28%) |
| **Storage Disk** | 916 GB (89 GB used / 11%) |
| **Load** | ~0.16 (very low) |

### Docker Containers (linux-server)

| Container | Purpose | Weblink |
|-----------|---------|---------|
| openclaw | OpenClaw agent framework | (local) |
| ollama-dashboard | Ollama LLM dashboard | http://192.168.1.247:8501 |
| dashboard | Crypto dashboard | http://192.168.1.247:5000 |
| ollama | Ollama LLM runtime | http://192.168.1.247:11434 |
| mini-llm-app | Mini LLM app (Streamlit) | http://192.168.1.247:8501 |
| producer/consumer | Sentiment Kafka pipeline | (internal) |
| naimi/wordpress | WordPress sites | http://192.168.1.247:80 |
| zookeeper | Kafka ZooKeeper | localhost:2181 |
| n8n | Workflow automation | http://192.168.1.247:5678 |
| sentiment-postgres | PostgreSQL | localhost:5432 |
| openbb | Finance terminal | http://192.168.1.247:6900 |
| naimi_db/wordpress_db | MySQL databases | localhost:3306 |
| python-kg | Knowledge graph | http://192.168.1.247:5071 |
| sd-synth-data | SD synthetic data | http://192.168.1.247:8501 |
| traefik | Reverse proxy | http://192.168.1.247:8080 |
| portainer | Container management | http://192.168.1.247:9000 |
| photoprism | Photo management | http://192.168.1.247:2342 |
| plex | Media server | http://192.168.1.247:32400 |
| audiobookshelf | Audiobook server | http://192.168.1.247:80 |
