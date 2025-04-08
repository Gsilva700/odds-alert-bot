# odds-alert-bot

# Odds Alert Bot

Sistema completo para criação e gerenciamento de alertas de odds esportivas com envio via Telegram.

## Como executar

1. Instale as dependências:
```bash
pip install fastapi uvicorn sqlalchemy jinja2 passlib[bcrypt] python-jose requests
```

2. Inicie o servidor:
```bash
uvicorn main:app --reload
```

3. Acesse no navegador:
```
http://127.0.0.1:8000
```

## Funcionalidades

- Cadastro de usuários (manual no banco).
- Criação e listagem de alertas por usuário.
- Integração com Telegram.
- Interface Web para login e dashboard.
