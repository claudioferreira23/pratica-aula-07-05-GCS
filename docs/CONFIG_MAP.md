# CONFIG_MAP.md

# Mapa de Configuração do Projeto

## Projeto
**Weather App**

Aplicação desktop desenvolvida em Python utilizando PyQt5 para consulta de informações climáticas através da API OpenWeatherMap.

---
## Versionamento

O projeto utiliza o padrão de Versionamento Semântico (Semantic Versioning - SemVer) para controlar e identificar as versões do sistema de forma organizada e padronizada.

```
O formato utilizado é:

MAJOR.MINOR.PATCH

Exemplo:

v1.0.0

Cada parte da versão possui um significado específico:

MAJOR: incrementado quando ocorrem mudanças incompatíveis ou alterações que quebram compatibilidade com versões anteriores.
MINOR: incrementado quando novas funcionalidades compatíveis são adicionadas ao sistema.
PATCH: incrementado para correções de bugs, melhorias internas e pequenos ajustes sem impacto na compatibilidade.

Exemplos de evolução:

v1.0.0 → v1.1.0
```

---

# 1. Itens de Configuração (ICs)

Os itens de configuração representam todos os artefatos que precisam ser controlados durante o desenvolvimento e manutenção do sistema.

---

## 1.1 Código-Fonte

| ID | Item de Configuração | Descrição | Tipo | Versão |
|---|---|---|---|---|
| IC-01 | `src/main.py` | Arquivo principal da aplicação | Código-fonte | v1.0.0 |

---

## 1.2 Arquivos de Configuração

| ID | Item de Configuração | Descrição | Tipo |Versão |
|---|---|---|---|---|
| IC-02 | `config/config.env` | Variáveis de ambiente da aplicação | Configuração | v1.0.0 |
| IC-03 | `requirements.txt` | Dependências do projeto | Configuração | v1.0.0 |
| IC-04 | `.gitignore` | Arquivos ignorados pelo Git | Configuração | v1.0.0 |

---

## 1.3 Documentação

| ID | Item de Configuração | Descrição | Tipo |Versão |
|---|---|---|---|---|
| IC-05 | `README.md` | Documentação principal do projeto | Documentação | v1.0.0 |
| IC-06 | `CONFIG_MAP.md` | Mapa de configuração do projeto | Documentação | v1.0.0 |

---

## 1.4 Bibliotecas e Frameworks

| ID | Item | Versão | Tipo |Versão |
|---|---|---|---|---|
| IC-07 | Python | 3.x | Linguagem | v1.0.0 |
| IC-08 | PyQt5 | 5.x | Framework GUI | v1.0.0 |
| IC-09 | Requests | 2.x | Biblioteca HTTP | v1.0.0 |
| IC-10 | python-dotenv | 1.x | Biblioteca de variáveis de ambiente | v1.0.0 |

---

## 1.5 Serviços Externos

| ID | Serviço | Descrição |Versão |
|---|---|---|---|
| IC-11 | OpenWeatherMap API | Serviço externo para obtenção de dados climáticos | v1.0.0 |

---

## 1.5 Politíca de versionamento

| ID | Item | Descrição Versão |
|---|---|---|---|---|
| IC-12 | Tag | Versinamento semântico | v1.0.0 |