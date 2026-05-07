# pratica-aula-07-05-GCS

# 🌦️ Weather App

Aplicação desktop desenvolvida em Python utilizando PyQt5 para consultar informações climáticas em tempo real através da API OpenWeatherMap.

---

# 📌 Funcionalidades

- Consulta de clima por cidade
- Exibição da temperatura em Celsius
- Exibição da descrição do clima
- Emojis dinâmicos para condições climáticas
- Tratamento de erros HTTP
- Interface gráfica moderna com PyQt5

---

# 🖼️ Interface

O sistema possui uma interface simples e intuitiva contendo:

- Campo para digitar o nome da cidade
- Botão para buscar informações climáticas
- Exibição de:
  - temperatura
  - descrição do clima
  - emoji correspondente

---

# 🚀 Tecnologias Utilizadas

- Python 3
- PyQt5
- Requests
- OpenWeatherMap API

---

# 📂 Estrutura do Projeto

```text
pratica-aula-07-05-GCS/
│
├── config
├── scripts
├── docs
    └── requisitos.md
├── src
    └── main.py
├── tests
├── README.md
└── requirements.txt

```

# Como executar

```bash
## Instalar dependências

pip install -r requirements.txt

python src/main.py