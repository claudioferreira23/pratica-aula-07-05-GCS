# CONFIG_MAP.md

# Mapa de Configuração do Projeto

## Projeto
**Weather App**

Aplicação desktop desenvolvida em Python utilizando PyQt5 para consulta de informações climáticas através da API OpenWeatherMap.

---

# 1. Itens de Configuração (ICs)

Os itens de configuração representam todos os artefatos que precisam ser controlados durante o desenvolvimento e manutenção do sistema.

---

## 1.1 Código-Fonte

| ID | Item de Configuração | Descrição | Tipo |
|---|---|---|---|
| IC-01 | `src/main.py` | Arquivo principal da aplicação | Código-fonte |

---

## 1.2 Arquivos de Configuração

| ID | Item de Configuração | Descrição | Tipo |
|---|---|---|---|
| IC-02 | `config/config.env` | Variáveis de ambiente da aplicação | Configuração |
| IC-03 | `requirements.txt` | Dependências do projeto | Configuração |
| IC-04 | `.gitignore` | Arquivos ignorados pelo Git | Configuração |

---

## 1.3 Documentação

| ID | Item de Configuração | Descrição | Tipo |
|---|---|---|---|
| IC-05 | `README.md` | Documentação principal do projeto | Documentação |
| IC-06 | `CONFIG_MAP.md` | Mapa de configuração do projeto | Documentação |

---

## 1.4 Bibliotecas e Frameworks

| ID | Item | Versão | Tipo |
|---|---|---|---|
| IC-07 | Python | 3.x | Linguagem |
| IC-08 | PyQt5 | 5.x | Framework GUI |
| IC-09 | Requests | 2.x | Biblioteca HTTP |
| IC-10 | python-dotenv | 1.x | Biblioteca de variáveis de ambiente |

---

## 1.5 Serviços Externos

| ID | Serviço | Descrição |
|---|---|---|
| IC-11 | OpenWeatherMap API | Serviço externo para obtenção de dados climáticos |

---