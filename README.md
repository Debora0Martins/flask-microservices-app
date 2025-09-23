🚀 Projeto CI/CD + Kubernetes (Primeira Entrega)
📌 Descrição

Aplicação Flask simples, Dockerizada, servindo como base para evoluir em um pipeline de CI/CD com GitHub Actions, além de futura orquestração em Kubernetes e deploy na AWS.

Este projeto é a primeira entrega do meu portfólio de Engenharia de Software/DevOps.

🛠️ Tecnologias usadas

Python 3.11

Flask

Docker

GitHub

📂 Estrutura do projeto
projeto-ci-cd/
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md

▶️ Como rodar localmente
1. Usando Python diretamente
# Criar ambiente virtual
python -m venv venv
venv\Scripts\activate  # Windows
# ou source venv/bin/activate (Linux/Mac)

# Instalar dependências
pip install -r requirements.txt

# Rodar app
python app.py


👉 Acesse: http://localhost:5000

2. Usando Docker
# Build da imagem
docker build -t meu-app-flask .

# Rodar container
docker run -p 5000:5000 meu-app-flask


👉 Acesse: http://localhost:5000

🎯 Próximos passos

 Criar pipeline CI/CD com GitHub Actions

 Deploy automatizado na AWS

 Orquestração com Kubernetes

 Adicionar monitoramento e logs

✍️ Autora: Débora Martins
📧 Email: ddeboraf.mar@gmail.com

🌍 GitHub: @Debora0Martins
