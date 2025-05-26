## 📊 6º Trabalho de Compensação – UC22: Ciências de Dados

**Curso:** Ensino Médio Técnico em Informática
 **Aluno:** [Nome do Aluno]
 **Turma:** [3ºC]
 **Professor:** André Ricardo da Silva
 **Entrega até:** [Definir data]

------

### 🎯 Tema Geral

Pré-processamento de dados: coleta, limpeza, normalização e tipos de variáveis.

------

### 📁 Estrutura do Trabalho

O trabalho será dividido em **quatro partes**, com foco em teoria, prática e reflexão:

------

### 📝 Parte 1 – Documento Textual (.docx ou .pdf)

#### 📌 Tema: Fundamentos do Pré-processamento e Classificação de Dados

**Sugestão de estrutura:**

1. **Introdução**
   - O que é Ciência de Dados e por que é importante?
   - Como a qualidade dos dados impacta o resultado das análises?
2. **Coleta de Dados**
   - Formas comuns de coleta (planilhas, formulários, APIs).
   - Exemplo prático: coleta de dados da sala (idade, gênero, nota etc.).
3. **Pré-processamento de Dados**
   - **Limpeza:** remoção de dados ausentes, duplicados ou inválidos.
   - **Normalização:** padronização de formatos (ex: datas, unidades).
   - Exemplos ilustrativos (valores faltantes, erros de digitação, escalas diferentes).
4. **Tipos e Classificação de Variáveis**
   - Tipos: qualitativas (nominais, ordinais) e quantitativas (discretas, contínuas).
   - Exemplos práticos com dados da escola: nota, idade, série, gênero, presença etc.
5. **Conclusão**
   - O que o aluno compreendeu sobre a importância de preparar os dados antes de analisá-los.

------

### 🎤 Parte 2 – Apresentação (.pptx ou .pdf)

#### 🎯 Tema: Como tratar dados antes da análise

**Sugestão de slides:**

1. Slide 1: Título, nome, turma
2. Slide 2: O que é pré-processamento?
3. Slide 3: Etapas: coleta → limpeza → normalização
4. Slide 4: Exemplos de erros nos dados (valores nulos, formatos diferentes, dados inconsistentes)
5. Slide 5: Tipos de variáveis explicados com exemplos visuais
6. Slide 6: Conclusão e aprendizados

------

### 🧪 Parte 3 – Atividade Prática

#### 🅰️ Opção A – Planilha de Dados (Excel, LibreOffice, Google Sheets)

1. Criar uma planilha com ao menos **10 registros** contendo:
   - Nome, Idade, Nota, Gênero, Status de presença, Curso
2. Simular dados sujos:
   - Linhas com idade ausente, nota com vírgula e ponto misturados, gênero escrito com variações
3. Criar nova aba "Tratado" com dados limpos
4. Inserir observações explicando o que foi feito

#### 🅱️ Opção B – Código Python (iniciante)

1. Criar um dicionário com os dados acima
2. Tratar os dados com:
   - Remoção de nulos, padronização de gênero, conversão de nota para float
3. Mostrar os dados antes e depois do tratamento

> *Caso o aluno não tenha domínio de programação, recomenda-se optar pela planilha.*

------

### 🎬 Parte 4 – Vídeo Explicativo (2 a 4 minutos)

#### 🎥 Roteiro sugerido:

1. **Apresentação e Tema (30s):**
    "Olá, sou [Seu Nome], e esse é meu trabalho da UC22 sobre pré-processamento e tipos de dados."
2. **Explicação Conceitual (1 min):**
    "Antes de fazer qualquer análise, é preciso garantir que os dados estejam corretos."
3. **Demonstração Prática (1–2 min):**
    "Aqui está minha planilha com os dados antes e depois do tratamento..."
4. **Encerramento (30s):**
    "Esse processo é essencial para garantir a validade das decisões. Obrigado por assistir."

------

### 📦 Entregáveis

- ✅ Documento textual (.docx ou .pdf)
- ✅ Apresentação (.pptx ou .pdf)
- ✅ Atividade prática (planilha ou script Python)
- ✅ Vídeo explicativo (Google Drive, YouTube não listado, Loom etc.)

------

### 🧰 Ferramentas Recomendadas

| Finalidade | Ferramentas                            |
| ---------- | -------------------------------------- |
| Texto      | Google Docs, Word                      |
| Slides     | PowerPoint, Google Slides              |
| Planilha   | Google Sheets, Excel, LibreOffice Calc |
| Código     | VSCode, Colab, Jupyter                 |
| Vídeo      | OBS, celular, Loom, Screencast         |

------

## 📂 Arquivos de Referência do Aluno

- `uc22_trabalho_dados_sujos_e_limpos.xlsx`
- `video_explicativo.mp4` ou link
- `documento_teorico.pdf`
- `apresentacao_uc22.pdf`

------

## 📊 Tipos de Variáveis (Exemplo Usado)

| Variável | Tipo de Dado | Classificação |
| -------- | ------------ | ------------- |
| Nome     | Qualitativo  | Nominal       |
| Idade    | Quantitativo | Discreto      |
| Nota     | Quantitativo | Contínuo      |
| Gênero   | Qualitativo  | Nominal       |
| Presença | Qualitativo  | Nominal       |
| Curso    | Qualitativo  | Nominal       |

------

## 🐍 Exemplo de Código Python para Limpeza de Dados

```python
import pandas as pd

# Carregar dados (exemplo em dicionário)
dados = {
    "Nome": ["Ana", "Carlos", "Fernanda"],
    "Nota": ["8,5", "7.5", "6,0"],
    "Gênero": ["FEM", "masculino", "Feminino"]
}
df = pd.DataFrame(dados)

# Limpeza de nota
df["Nota"] = df["Nota"].str.replace(",", ".").astype(float)

# Padronização de gênero
map_genero = {
    "fem": "Feminino", "feminino": "Feminino", "masculino": "Masculino"
}
df["Gênero"] = df["Gênero"].str.lower().map(map_genero)

print(df)
```

------

## 📌 Conclusão

Este trabalho demonstrou como o tratamento adequado dos dados é essencial para garantir a validade das análises em Ciência de Dados. A limpeza, padronização e identificação dos tipos de variáveis são etapas cruciais antes de qualquer análise estatística ou modelagem.