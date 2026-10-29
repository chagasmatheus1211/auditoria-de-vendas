# 🛡️ Sistema de Auditoria de Vendas (Security Analysis)

## 📝 Descrição do Projeto

Este projeto consiste em uma ferramenta de **análise e auditoria de transações financeiras** desenvolvida em Python. O sistema foi projetado para identificar anomalias em fluxos de vendas, agindo como uma camada de segurança inicial para departamentos financeiros.

O script processa entradas de vendas, calcula métricas de desempenho e aplica regras de negócio para detectar valores atípicos (*outliers*) ou volumes que excedam limites de segurança preestabelecidos. Caso uma irregularidade seja detectada, o sistema solicita uma intervenção manual, permitindo o ajuste dinâmico de parâmetros globais de segurança.

## ⚙️ Funcionalidades Principais

- 📊 **Cálculo de Médias:** processamento automatizado de volumes de venda para geração de indicadores.
- 🚨 **Detecção de Quarentena:** alerta imediato caso a média das transações ultrapasse o `LIMITE_SEGURANCA`.
- 🔎 **Revisão de Outliers:** identificação de vendas suspeitas que superam em 5 vezes a média do período.
- 🔧 **Ajuste Dinâmico:** interface via console para validação de legitimidade e reconfiguração de limites em tempo real.
- 🧪 **Log de Tipagem:** inspeção detalhada de tipos de dados para garantir a integridade do processamento numérico.

## 🚀 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Paradigma](https://img.shields.io/badge/Paradigma-Estruturado-6A5ACD?style=for-the-badge)
![Status](https://img.shields.io/badge/Projeto-Acadêmico-orange?style=for-the-badge)

- 🐍 **Linguagem:** Python 3.x
- 🧩 **Paradigma:** Programação Estruturada
- 💻 **Ambiente de Execução:** Terminal, Google Colab ou Jupyter Notebook

## 📊 Regras de Negócio e Lógica

O sistema opera com base em dois pilares críticos:

1. 🔐 **Segurança Global:** se a média das vendas for maior que o limite de segurança, o sistema entra em estado de quarentena.
2. 🕵️ **Integridade Individual:** se uma venda for maior ou igual a 5 vezes a média, uma revisão manual será solicitada para investigar possíveis fraudes ou erros de digitação.

## 📂 Estrutura do Projeto

```text
projeto-limite-de-seguranca/
├── README.md
└── main.py
```

- 📘 `README.md`: documentação e apresentação do projeto.
- 🐍 `main.py`: código-fonte do sistema de auditoria.

## 🔧 Como Executar

### 1. 📥 Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

> Substitua o endereço acima pelo endereço real do repositório no GitHub.

### 2. 📁 Acesse a pasta do projeto

```bash
cd SEU-REPOSITORIO/projeto-limite-de-seguranca
```

### 3. ▶️ Execute o programa

```bash
python main.py
```

### 4. ⌨️ Interaja com o sistema

Insira os valores das três últimas vendas quando solicitado pelo terminal. Se o sistema detectar uma venda suspeita, responda com `s` (sim) ou `n` (não) para prosseguir com a auditoria.

## 💻 Acesse o Projeto

🐍 **[Visualizar código-fonte (py.py)](py.py)**

## 👨‍💻 Autor

**Matheus Chagas Mauriz Coque**

🎓 Estudante de Engenharia de Software

🔗 [GitHub](https://github.com/chagasmatheus1211)

🔗 [LinkedIn](https://www.linkedin.com/in/matheus-chagas-coque-b190ba39b/)

---
