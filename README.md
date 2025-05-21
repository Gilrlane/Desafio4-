# 💼 Desafio 4 – Análise de Evasão de Clientes Bancários

Este projeto apresenta uma **análise exploratória de dados** com foco na evasão de clientes de uma instituição financeira. O objetivo é entender quem são os clientes que encerraram suas contas e oferecer insights valiosos para estratégias de retenção.

---

## 🎯 Objetivos

- 📌 Identificar o perfil dos clientes que saíram do banco.  
- 🧠 Analisar dados como idade, saldo e patrimônio.  
- 📊 Criar gráficos para visualização de padrões.  
- 📝 Redigir um relatório técnico para tomada de decisão.

---

## 🗂️ Arquivos do Projeto

- 📘 [Código do Projeto (Jupyter Notebook)](https://github.com/Gilrlane/Desafio4-/blob/f61cca55442fa85ec3465f16086afdd4f3d07e95/Desafio4.ipynb)  
- 📄 [Relatório em PDF](https://github.com/Gilrlane/Desafio4-/blob/f61cca55442fa85ec3465f16086afdd4f3d07e95/relatorio_analise_clientes.pdf)  

---

## 🛠️ Tecnologias Utilizadas

- 🐍 Python  
- 🧮 Pandas  
- 📈 Matplotlib  
- 🎨 Seaborn  
- 💻 Jupyter Notebook / VS Code  

---

## 📉 Análises Realizadas

- 📊 Estatísticas com `describe()`:
  - Saldo na conta
  - Idade
  - Patrimônio

- 🧹 Limpeza de Dados:
```python
df = df.drop_duplicates()
```

- 🧾 Foco em clientes que saíram:
```python
df_saiu = df[df['saiu'] == 1]
```

- 📌 Agrupamentos:
```python
df.groupby('genero')['saldo_na_conta'].mean()
df.groupby('estado')['saldo_na_conta'].mean()
```

- 📊 Gráficos criados:
  - Histograma da idade
  - Saldo por gênero
  - Evasão por estado

---

## 🔍 Principais Insights

- 👩 Gênero predominante: **Feminino**  
- 📅 Idade média: **44,5 anos**  
- 💰 Saldo médio: **R$ 8.523.988,16**  
- 🪙 Patrimônio médio: **R$ 4,73** | Mediano: **R$ 5,00**  
- 📍 Estados com mais evasão: **PI**, **MA**, **CE**, **RP**  

---

## 🚀 Próximos Passos

- 🤖 Aplicar modelos de predição (Machine Learning)  
- 📊 Construir dashboards interativos  
- 🕵️‍♀️ Analisar comportamento por faixa etária

---

## 👩‍💻 Autora

Feito com dedicação por [**Gilrlane**](https://www.linkedin.com/in/gilrlane/)  
🔗 Repositório GitHub: [Gilrlane/Desafio4-](https://github.com/Gilrlane/Desafio4-)

---
