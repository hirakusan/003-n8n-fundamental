# 🐳 003-n8n-fundamental Setup Proyek Docker dengan n8n, Ollama, Grafana, Kuma, dan Lainnya

docker-compose up -d

.
├── config
│   ├── grafana
│   └── nginx
├── data
│   ├── grafana_data
│   ├── kuma_data
│   ├── n8n_data
│   └── ollama_data
├── logs
│   ├── grafana
│   ├── n8n
│   ├── ollama
│   └── postgres
├── scripts
├── docs
└── docker-compose.yml

🔁 Tips Tambahan
Pastikan Docker Desktop telah diizinkan mengakses drive tempat proyek ini berada.

Pastikan image ollama/ollama sudah siap atau akan otomatis ditarik dari Docker Hub.

Jika kamu ingin menggunakan model Ollama dari sistem lokal (Windows), pastikan volume diarahkan ke:

/mnt/c/Users/<USERNAME>/.ollama:/root/.ollama
