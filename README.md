# 🧠 RNN - Redes Neurais Recorrentes: Deep Learning com PyTorch

Repositório destinado às atividades e exercícios do curso **"RNN - Redes Neurais Recorrentes: Deep Learning com PyTorch"** da [Alura](https://cursos.alura.com.br/course/rnn-redes-neurais-recorrentes-deep-learning-pytorch).

Os notebooks são desenvolvidos no **Google Colab** e versionados aqui no GitHub, com descrições do que foi implementado em cada aula.

---

## 📚 Sobre o Curso

O curso é voltado para pessoas desenvolvedoras que já possuem conhecimento dos fundamentos de redes neurais e desejam aplicar **Deep Learning a dados sequenciais** — como texto, voz e séries temporais.

O foco principal é na arquitetura **RNN (Recurrent Neural Network)** e suas variações, utilizando o framework **PyTorch** para implementações práticas.

---

## 🗂️ Conteúdo Abordado

### 1. Introdução a Dados Sequenciais
- O que são dados sequenciais e por que as RNNs são adequadas para esse tipo de dado
- Diferenças entre redes tradicionais (MLPs) e redes recorrentes

### 2. Implementação Prática de RNN
- Criação de uma RNN para classificar a **nacionalidade de sobrenomes** a partir dos caracteres das palavras
- Entendimento do fluxo de dados em redes recorrentes

### 3. Variações da Arquitetura RNN
- **LSTM (Long Short-Term Memory)**: como resolve o problema do gradiente desvanescente
- **GRU (Gated Recurrent Unit)**: versão simplificada da LSTM
- **RNNs Bidirecionais**: processamento da sequência nos dois sentidos
- **RNNs Profundas (Deep RNNs)**: empilhamento de camadas recorrentes

### 4. Análise de Sentimentos com RNN
- Aplicação prática para **classificação de texto e sentimentos**
- Pré-processamento de texto e criação de vocabulário

### 5. Gerenciamento de Sequências de Tamanho Variável
- Utilização de ferramentas do PyTorch como o pacote **Torchtext**
- Manipulação eficiente de sequências com tamanhos diferentes (padding, packing)

### 6. Séries Temporais
- Pré-processamento de dados temporais
- Treinamento e avaliação de modelos para **previsão de séries temporais**

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Descrição |
|---|---|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Linguagem principal |
| ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) | Framework de Deep Learning |
| ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white) | Ambiente de desenvolvimento |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | Notebooks interativos |

---

## 📁 Estrutura do Repositório

```
📦 Redes-Neurais-Recorrentes-Deep-Learning-com-PyTorch
 ┣ 📂 notebooks/         # Notebooks desenvolvidos por aula/atividade
 ┣ 📂 data/              # Datasets utilizados nos exercícios
 ┗ 📄 README.md
```

---

## 📋 Pré-requisitos

Para aproveitar bem este curso, é recomendado ter conhecimento prévio em:

- Fundamentos de redes neurais (feedforward, funções de ativação, backpropagation)
- Funções de perda e otimizadores
- Conceitos básicos de PyTorch (tensores, autograd, `nn.Module`)

---

## 🔗 Links Úteis

- 🎓 [Página do Curso na Alura](https://cursos.alura.com.br/course/rnn-redes-neurais-recorrentes-deep-learning-pytorch)
- 🔥 [Documentação do PyTorch](https://pytorch.org/docs/stable/index.html)
- 📖 [Torchtext](https://pytorch.org/text/stable/index.html)

---

> 📌 *Este repositório é atualizado conforme as atividades do curso são concluídas.*
