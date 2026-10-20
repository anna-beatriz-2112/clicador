# Clicador em Python 🚀

Site simples desenvolvido com servidor HTTP nativo em Python e persistência de dados.

## Funcionalidades
- Servidor web nativo utilizando o módulo `http.server` do Python.
- Contador de cliques com persistência no servidor (arquivo `counter.json`), mantendo os dados mesmo após atualizar a página (F5).
- Interface moderna, responsiva e com efeito de vidro (glassmorphism).

## Como Executar Localmente

1. Crie e ative o ambiente virtual (`venv`):
```bash
python -m venv venv
# No Windows (PowerShell):
.\venv\Scripts\Activate.ps1
# Ou no CMD:
.\venv\Scripts\activate.bat
```

2. Instale as dependências (se houver):
```bash
pip install -r requirements.txt
```

3. Inicie o servidor:
```bash
python server.py
```
Abra o navegador em: [http://localhost:8000](http://localhost:8000)
