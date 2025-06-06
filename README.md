# 📊 Student Performance Analysis

Este projeto realiza uma análise exploratória e preditiva sobre o desempenho acadêmico de estudantes com base em seus hábitos, utilizando um dataset público do Kaggle.

## 📁 Estrutura do Projeto

```
student_performance_analysis/
│
├── data/
│   └── Student_Habits.csv            # Dataset com hábitos e performance dos alunos
│
├── notebooks/
│   └── student_analysis.ipynb        # Notebook com análise exploratória e modelo
│
├── requirements.txt                  # Lista de dependências
└── README.md                         # Instruções do projeto
```

## 🚀 Como executar

1. **Clone ou extraia o repositório**:
   ```bash
   unzip student_performance_analysis_with_data.zip
   cd student_performance_analysis
   ```

2. **Crie e ative um ambiente virtual**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate       # Windows: .venv\Scripts\activate
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Abra o notebook no VS Code ou Jupyter**:
   ```
   notebooks/student_analysis.ipynb
   ```

## 📌 O que o notebook faz

- Carregamento e inspeção dos dados
- Análise exploratória com visualizações
- Pré-processamento com codificação e normalização
- Treinamento de um modelo de Random Forest
- Avaliação do modelo com métricas de classificação

## 📚 Fonte dos dados

Dataset original: [Student Habits vs Academic Performance - Kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)

## 📚 Vídeo com explicação
https://youtu.be/nweq6vRVfp8