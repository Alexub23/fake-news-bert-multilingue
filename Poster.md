# 🧾 Poster - Detecção de Fake News com BERT Multilíngue

## 📌 Descrição

Este diretório contém o poster acadêmico do projeto de detecção de fake news em textos utilizando modelos de linguagem baseados em BERT.

O estudo compara duas abordagens principais:

- Fine-tuning completo do BERT
- Arquitetura MAD-X com Adapters

---

## 🎯 Objetivo do projeto

Investigar e comparar a eficiência de diferentes estratégias de adaptação de modelos de linguagem para a tarefa de classificação de fake news em textos.

---

## 🧠 Metodologia

### 🔹 Fine-tuning
- Modelo base: bert-base-multilingual-uncased
- Ajuste completo de todos os parâmetros do modelo
- Treinamento supervisionado

### 🔹 MAD-X (Adapters)
- Uso da biblioteca Adapters (Hugging Face)
- Adapters linguísticos (EN/PT)
- Task adapter para classificação
- Treinamento eficiente com menor custo computacional

---

## 📚 Datasets utilizados

- Fake.br Corpus (Português)
- WELFake Dataset (Inglês)

---

## 🏗️ Arquitetura

### Fine-tuning
Texto → Tokenizer → BERT → Classificação (Fake/Real)

### MAD-X
Texto → Tokenizer → BERT + Adapters → Task Adapter → Classificação

---

## 📊 Métricas de avaliação

- Accuracy
- Precision
- Recall
- F1-score

---

## 📈 Resultados

https://cdn.phototourl.com/free/2026-06-11-11e8a688-105a-4b0f-8a09-d2edb88e4299.png

## 📌 Conclusão

O uso de Adapters reduz significativamente o custo computacional mantendo desempenho competitivo em relação ao fine-tuning tradicional.

O fine-tuning completo pode alcançar alta performance, porém exige maior poder computacional.

---

## 🛠️ Tecnologias utilizadas

- Python
- PyTorch
- Transformers (Hugging Face)
- Adapters (MAD-X)
- Scikit-learn
- Datasets

---

## 👨‍💻 Autor

Projeto acadêmico de Processamento de Linguagem Natural (NLP) com foco em detecção de fake news utilizando modelos BERT.
