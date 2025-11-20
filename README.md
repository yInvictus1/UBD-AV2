# 🧠 Projetos de Análise de Dados — Minimundos

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB?logo=python)](https://seaborn.pydata.org/)  
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)  
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red)](#-autor)

---

## 📚 Índice

1. [🩺 Minimundo 4 — Relação entre IMC e Pressão Arterial](#-minimundo-4--relação-entre-imc-e-pressão-arterial)  
2. [💉 Minimundo 6 — Eficácia de Vacinas](#-minimundo-6--eficácia-de-vacinas)  
3. [⚙️ Execução](#️-execução)  
4. [📊 Autor](#-autor)

---

## 🩺 Minimundo 4 — Relação entre IMC e Pressão Arterial

**Contexto:**  
Uma clínica busca entender como a **idade** e o **índice de massa corporal (IMC)** se relacionam com a **pressão arterial sistólica** de seus pacientes.

**Tarefas realizadas:**
- Calcular médias e correlações entre IMC e pressão arterial.  
- Gerar gráfico de dispersão (*idade × pressão*).  
- Criar mapa de calor com a matriz de correlação.

**Bibliotecas utilizadas:**  
`pandas`, `seaborn`

**Arquivo base:** `pressao_arterial.csv`

| paciente | idade | imc | pressao_sistolica |
|-----------|-------|-----|-------------------|
| 1 | 25 | 22.4 | 118 |
| 2 | 40 | 27.1 | 132 |
| 3 | 55 | 30.2 | 146 |
| 4 | 65 | 31.8 | 155 |
| 5 | 35 | 25.7 | 128 |

---

## 💉 Minimundo 6 — Eficácia de Vacinas

**Contexto:**  
Um estudo avalia a **resposta imune** (nível de anticorpos) gerada por diferentes vacinas em pessoas de idades variadas.

**Tarefas realizadas:**
- Calcular média de anticorpos por tipo de vacina.  
- Plotar boxplot comparativo e mapa de calor.  
- Gerar gráfico de dispersão (*idade × anticorpos*).

**Bibliotecas utilizadas:**  
`pandas`, `seaborn`

**Arquivo base:** `vacinas.csv`

| vacina | idade | anticorpos |
|---------|-------|-------------|
| A | 30 | 1150 |
| A | 40 | 1280 |
| B | 30 | 1400 |
| B | 45 | 1350 |
| C | 35 | 1000 |

---

## ⚙️ Execução

Para rodar os notebooks ou scripts localmente:

```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/minimundos-analise-dados.git
cd minimundos-analise-dados

## Integrantes

- Diego Rosa  
- Patrícia Silva  
- Nathaly Pereira  
- Gustavo Sthel  
- Camila Barcelos  


# Instale as dependências
pip install pandas seaborn matplotlib

# Execute no ambiente de sua preferência (ex: Jupyter Notebook, VSCode ou Google Colab)
