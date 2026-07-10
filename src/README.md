# Passo a Passo de Execução

## Setup do Ollama

```bash
# 1. Instalar Ollama (ollama.com)
# 2. Baixar um modelo leve
ollama pull llama3.2

# 3. Testar se funciona
ollama run llama3.2 "Olá!"
```

## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Como Rodar

```bash
# 1. Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que Ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run app.py
```

## Evidência de Execução

<img width="1341" height="840" alt="projeto dio agente financeiro" src="https://github.com/user-attachments/assets/1795441a-f473-48e8-bab0-1c3c08761897" />
