# Proejto: Servidor MCP de Automação Residencial

## Descrição 
Projeto com foco no estudo de servidores MCP

## Funcionalidades

- Comandos via terminal para:
  - Ligar/desligar luzes
  - Ajustar temperatura
  - Trancar/destrancar portas
  - Ver status geral

## Estrutura do Projeto
```
mcp_server/
├── server.py              # Servidor principal
├── processor/
│   ├── __init__.py        # Torna o pacote importável
│   ├── commands.py        # Processamento dos comandos
│   ├── actions/
│   │   ├── __init__.py
│   │   ├── lights.py      # Comandos de luz
│   │   ├── door.py        # Comandos de porta
│   │   └── temperature.py # Comando de temperatura
├── client.py              # Cliente para testes

```