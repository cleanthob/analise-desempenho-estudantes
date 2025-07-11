# 📊 Student Habits & Performance Analysis

Este projeto realiza uma análise exploratória de dados (EDA) para entender como os hábitos diários dos estudantes influenciam seu desempenho em exames.

## 🧠 Objetivo

O objetivo principal é investigar a correlação entre fatores como tempo de estudo, uso de redes sociais, horas de sono, saúde mental, entre outros, e a nota final dos estudantes.

## 📁 Fonte da Base de Dados

- **Dataset**: [Student Habits vs Academic Performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)

## 📁 Estrutura dos Dados

O conjunto de dados contém 1.000 registros com as seguintes colunas:

- `student_id`: Identificador do estudante  
- `age`: Idade  
- `gender`: Gênero  
- `study_hours_per_day`: Horas de estudo por dia  
- `social_media_hours`: Horas gastas em redes sociais  
- `netflix_hours`: Horas gastas assistindo Netflix  
- `part_time_job`: Possui emprego de meio período (Sim/Não)  
- `attendance_percentage`: Porcentagem de presença  
- `sleep_hours`: Horas de sono por dia  
- `diet_quality`: Qualidade da alimentação (`Poor`, `Fair`, `Good`)  
- `exercise_frequency`: Frequência de exercícios físicos  
- `parental_education_level`: Escolaridade dos pais  
- `internet_quality`: Qualidade da internet (`Poor`, `Average`, `Good`)  
- `mental_health_rating`: Avaliação de saúde mental (1 a 10)  
- `extracurricular_participation`: Participa de atividades extracurriculares (Sim/Não)  
- `exam_score`: Nota do exame final

## 🛠️ Tecnologias Utilizadas

- Python 3  
- Pandas  
- Matplotlib  
- ydata-profiling (para geração de relatório EDA automatizado)

## 🔍 Análises Realizadas

- Visualização das primeiras linhas do dataset  
- Verificação de tipos de dados e valores ausentes  
- Cálculo de correlações entre variáveis numéricas  
- Análise dos principais fatores que afetam o desempenho (nota do exame)  
- Tratamento de dados nulos  

## 🧩 Principais Insights

- Existe uma **forte correlação positiva** entre as **horas de estudo por dia** e a **nota no exame**.  
- A **saúde mental** também apresentou **correlação positiva** com a performance.  
- **Uso excessivo de redes sociais e Netflix** está **negativamente correlacionado** ao desempenho.  

## 📄 Como Executar

1. Clone o repositório  
2. Certifique-se de ter o Python e as bibliotecas necessárias instaladas  
3. Execute o notebook `main.ipynb` em um ambiente como Jupyter, VSCode ou Google Colab  

```bash
pip install pandas matplotlib ydata-profiling
