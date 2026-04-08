# 📘 Miniguia de Estudos: Arquitetura RAG e Otimização de LLMs

Este repositório foi criado para o desafio de projeto da **DIO (Digital Innovation One)**. O objetivo é demonstrar o uso do **NotebookLM** como uma ferramenta de aprendizagem ativa para organizar conhecimentos sobre Inteligência Artificial e Engenharia de Prompt.

---

## 🎯 Contexto e Objetivos

O foco deste caderno temático é o estudo de **Sistemas RAG (Retrieval-Augmented Generation)**. 
Como desenvolvedor Full-Stack focado em Machine Learning, meu objetivo foi entender como conectar bases de dados externas (como SQL Server e PDFs técnicos) a modelos de linguagem para reduzir alucinações e aumentar a precisão técnica das respostas.

---

## 📚 Curadoria de Fontes
Para este estudo, selecionei e processei no NotebookLM as seguintes fontes:

1. **Documentação do Pinecone:** Guia sobre Bancos de Dados Vetoriais.
2. **Artigo Técnico "RAG vs Fine-tuning":** Uma análise de quando usar cada abordagem.
3. **AWS Whitepaper:** Boas práticas para deploy de modelos de ML em Cloud.
4. **Notebook de Referência:** Implementação de busca semântica com Python e Scikit-Learn.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Documentar o raciocínio por trás das perguntas é fundamental para extrair o melhor da IA. Abaixo, os testes realizados:

| Objetivo | Prompt Testado | Resultado / Dificuldade |
| :--- | :--- | :--- |
| **Visão Geral** | "Explique o que é RAG." | Resposta muito genérica. Precisei refinar para o contexto de desenvolvimento. |
| **Aplicação Técnica** | "Com base nas fontes, como estruturar um banco vetorial para dados vindos de um SQL Server?" | **Excelente.** A IA cruzou os dados da Fonte 1 com a lógica de pipelines de dados. |
| **Troubleshooting** | "Quais os gargalos de latência em sistemas RAG?" | Inicialmente a IA focou em hardware. Ajustei o prompt para focar em "latência de software e embeddings". |

---

## 🛠️ Miniguia de Estudo (Entrega Final)

### 📝 Resumo Estruturado
1. **Conceito Chave:** RAG combina a capacidade de geração dos LLMs com a precisão de sistemas de busca de dados.
2. **Fluxo de Trabalho:** Ingestão de dados -> Geração de Embeddings -> Armazenamento Vetorial -> Consulta (Retrieval) -> Geração de Resposta.
3. **Infraestrutura:** A escolha do banco (Pinecone, Milvus) e o modelo de embedding (OpenAI, HuggingFace) definem a precisão do sistema.

### 📖 Glossário
* **Embeddings:** Vetores numéricos que representam o significado de uma palavra ou frase.
* **Tokens:** Unidades de processamento de texto das LLMs.
* **Prompt Engineering:** A arte de formular perguntas para obter respostas precisas.

### ⚡ Prompts Reutilizáveis
* *"Crie um resumo executivo dos 3 principais pontos de segurança citados nos documentos."*
* *"Gere um exemplo de código Python para converter uma string em embedding usando a biblioteca sugerida nas fontes."*
* *"Identifique contradições entre a Fonte 2 e a Fonte 3 sobre custos de infraestrutura."*

---

## 👨‍💻 Autor
Desenvolvido por **Matheus**.
*Full-Stack Developer | Machine Learning & Cloud Enthusiast*
