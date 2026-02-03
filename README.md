# Telegram Chatbot de Temperatura (n8n)

Chatbot desenvolvido no n8n que informa a temperatura atual de cidades do Brasil via Telegram, utilizando a API do OpenWeather.

## Funcionalidades
- Recebe mensagens no formato: Cidade,UF
- Consulta a API OpenWeather
- Retorna a temperatura em graus Celsius
- Tratamento de erro para cidades inválidas

## Requisitos
- n8n
- Conta no Telegram
- Conta no OpenWeather

## Variáveis de Ambiente
Api key open weather: OPENWEATHER_API_KEY
Telegran token: TELEGRAN_API_TOKEN


## Importação
1. Acesse o n8n
2. Clique em Import Workflow
3. Selecione o arquivo `workflow-telegram-chatbot.json`
4. Configure as credenciais
5. Ative o workflow

## Exemplo de uso
Entrada: São Paulo, SP

Saída:
A temperatura em São Paulo é de 25°C.

