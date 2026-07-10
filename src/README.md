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

![projeto dio agente financeiro 4.png](../../../Documents/Cursos/Bootcamp%20Afya%20DIO/projeto%20dio%20agente%20financeiro%204.png)