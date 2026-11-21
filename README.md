# Agente de IA

Base inicial para experimentar e desenvolver um agente de IA em Python.

## Pré-requisitos

- Python 3.11 ou superior
- Git
- Uma conta no GitHub

## Configuração local

No PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -e ".[dev]"
Copy-Item .env.example .env
```

Execute o projeto:

```powershell
agente-ia
```

Execute os testes:

```powershell
pytest
```

## Próximos passos

1. Escolher o primeiro caso de uso do agente.
2. Escolher um provedor/modelo de IA.
3. Definir as ferramentas e fontes de dados do agente.
4. Criar uma avaliação simples antes de aumentar a complexidade.

Nunca salve chaves de API no Git. Use o arquivo `.env`, que já está ignorado.
