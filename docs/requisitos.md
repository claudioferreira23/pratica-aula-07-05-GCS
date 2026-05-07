# Requisitos do Sistema - Weather App

## 1. Visão Geral

O sistema **Weather App** é uma aplicação desktop desenvolvida em Python utilizando a biblioteca PyQt5.  
Seu objetivo é permitir que o usuário consulte informações climáticas de uma cidade em tempo real através da API OpenWeatherMap.

---

# 2. Requisitos Funcionais

## RF01 - Inserção do nome da cidade
O sistema deve permitir que o usuário informe o nome de uma cidade em um campo de texto.

## RF02 - Consulta de clima
O sistema deve consultar a API OpenWeatherMap ao clicar no botão **"Get Weather"**.

## RF03 - Exibição da temperatura
O sistema deve exibir a temperatura atual da cidade consultada em graus Celsius (°C).

## RF04 - Exibição da descrição do clima
O sistema deve exibir a descrição textual do clima retornada pela API.

Exemplo:
- clear sky
- rain
- clouds

## RF05 - Exibição de emoji climático
O sistema deve exibir um emoji correspondente à condição climática retornada pela API.

Exemplos:
- ☀️ para céu limpo
- 🌧️ para chuva
- ❄️ para neve

## RF06 - Tratamento de erros HTTP
O sistema deve tratar erros HTTP retornados pela API e exibir mensagens apropriadas ao usuário.

Exemplos:
- Cidade não encontrada
- Chave de API inválida
- Serviço indisponível

## RF07 - Limpeza das informações em caso de erro
O sistema deve limpar os campos de emoji e descrição climática quando ocorrer um erro.

---

# 3. Requisitos Não Funcionais

## RNF01 - Interface gráfica
O sistema deve possuir interface gráfica desenvolvida com PyQt5.

## RNF02 - Tempo de resposta
O sistema deve responder às consultas climáticas em tempo aceitável dependendo da conexão com a internet.

## RNF03 - Usabilidade
O sistema deve possuir interface simples e intuitiva para facilitar o uso.

## RNF04 - Compatibilidade
O sistema deve ser executado em ambientes que suportem Python 3 e PyQt5.

## RNF05 - Comunicação externa
O sistema deve utilizar requisições HTTP para comunicação com a API OpenWeatherMap.

## RNF06 - Estilização
O sistema deve utilizar estilização CSS via `setStyleSheet()` para melhorar a aparência visual.

---

# 4. Regras de Negócio

## RN01 - Conversão de temperatura
A temperatura recebida da API em Kelvin deve ser convertida para Celsius utilizando a fórmula:

```text
°C = K - 273.15