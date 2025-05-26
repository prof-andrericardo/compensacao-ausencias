## 🧠 2º Trabalho de Compensação – UC16: Armazenamento e Visualização de Dados

**Curso:** Ensino Médio Técnico em Informática
 **Aluno:** [Nome do Aluno]
 **Turma:** [3ºC]
 **Professor:** André Ricardo da Silva
 **Entrega até:** [Definir data]

------

### 📁 Estrutura do Trabalho

O trabalho será dividido em **quatro partes integradas**:

------

### 📝 **Parte 1 – Documento Textual (.docx ou .pdf)**

#### 📌 Tema: **Fundamentos de Banco de Dados e Modelagem Relacional**

**Estrutura sugerida do documento:**

1. **Introdução**
   - Conceito geral de banco de dados e sua importância.
2. **Técnicas e Tipos de Banco de Dados**
   - Definição e exemplos dos tipos (relacional, hierárquico, NoSQL etc.).
   - O que é SGDB e exemplos: MySQL, PostgreSQL, MongoDB.
   - Explicação de ETL e Big Data com exemplos simples.
3. **Modelagem Conceitual**
   - Etapas do levantamento de requisitos (técnicas de entrevista, observação).
   - Dicionário de dados: o que é e como construir.
   - Modelo Entidade-Relacionamento: explicação de entidades, atributos, relacionamentos e chaves.
   - Normalização (1FN, 2FN, 3FN) com exemplos simples.
4. **Modelagem Física**
   - Conceitos da linguagem SQL e principais comandos (DDL, DML, DQL).
   - Criação de tabelas e relacionamentos com chaves primárias e estrangeiras.
   - Comandos SELECT, WHERE, JOIN, GROUP BY, funções agregadas e subconsultas.
   - Procedimentos armazenados e gatilhos.
5. **Conclusão**
   - Aplicações práticas e importância da organização e otimização de dados.

------

### 🎤 **Parte 2 – Apresentação (.pptx ou .pdf)**

#### Tema: **Modelagem e Manipulação de Dados em Banco Relacional**

**Sugestão de Slides:**

- Slide 1: Capa com nome, turma e título.
- Slide 2: Diferença entre banco de dados e SGDB.
- Slide 3: Tipos de banco (relacional, NoSQL, etc.).
- Slide 4: Etapas da modelagem de dados.
- Slide 5: Exemplo de modelo ER com 3 entidades e relacionamentos.
- Slide 6: Dicionário de dados (tabela resumida).
- Slide 7: Normalização (exemplo de tabela antes/depois).
- Slide 8: Estrutura SQL criada na atividade prática.
- Slide 9: Prints de comandos executados (SELECT, JOIN, etc.).
- Slide 10: Conclusão e aprendizados.

------

### 🧪 **Parte 3 – Atividade Prática (SQL + DER)**

#### Desafio: **Criar e manipular um banco de dados relacional simples**

**📘 Tema sugerido:** Cadastro Escolar (aluno, turma, disciplina, chamada)

**Requisitos:**

1. Criar no MySQL (Workbench ou terminal):
   - Banco de dados: `escola_db`
   - Tabelas:
     - `alunos(id, nome, matricula)`
     - `turmas(id, nome, ano)`
     - `disciplinas(id, nome)`
     - `chamadas(id, data, aluno_id, turma_id, presenca)`
2. Criar relacionamento com chaves estrangeiras e aplicar integridade referencial.
3. Inserir 3 registros em cada tabela.
4. Executar comandos:
   - SELECT com filtros (`WHERE`).
   - JOIN entre `alunos` e `turmas`.
   - GROUP BY com contagem de presença.
   - Subconsulta (ex: alunos com mais de X presenças).
5. Criar pelo menos:
   - 1 **view** (visão).
   - 1 **procedimento armazenado** (ex: registrar presença).
   - 1 **gatilho (trigger)** (ex: impedir presenças duplicadas).

**🗂️ Entrega:**

- Arquivo `.sql` com todos os comandos.
- Imagem (ou PDF) do modelo ER (pode usar dbdiagram.io, Draw.io, MySQL Workbench ou feito à mão).
- Pasta `uc16_trabalho_nome.zip` com:
  - `modelo_ER.png`
  - `script.sql`
  - prints dos testes (opcional).

------

### 🎬 **Parte 4 – Vídeo Explicativo (3 a 6 minutos)**

#### 🎥 Roteiro Sugerido:

------

### 🎬 Introdução (20–30s)

**Fala:**
 "Olá! Eu sou [Seu Nome], e neste vídeo apresento o meu trabalho da UC16 – Armazenamento e Visualização de Dados. Vou mostrar o que aprendi sobre modelagem de dados e a criação de um banco de dados relacional no MySQL."

------

### 🔍 Parte 1: Conceitos (1 minuto)

**Fala:**
 "Comecei revisando os tipos de banco de dados. O mais comum é o relacional, usado aqui com MySQL. Também conheci conceitos como normalização, chaves primária e estrangeira e modelagem com entidades e relacionamentos."

------

### 🧱 Parte 2: Modelo ER (1 minuto)

**Fala:**
 "Com base no tema escolar, modelei um banco com as entidades `alunos`, `turmas`, `disciplinas` e `chamadas`. Usei relacionamentos com chaves estrangeiras e defini as regras de integridade entre elas."

------

### 💻 Parte 3: Execução SQL (2–3 minutos)

**Fala:**
 "Criei o banco e as tabelas no MySQL Workbench. Insiri registros e testei consultas usando comandos `SELECT`, `JOIN`, `GROUP BY`, e subconsultas. Também criei uma view para ver presenças por aluno, um procedimento armazenado para registrar chamada, e um trigger para evitar chamadas duplicadas."

------

### ✅ Conclusão (30s)

**Fala:**
 "Esse trabalho me ajudou a entender melhor como funciona a estrutura de um banco de dados e como aplicar boas práticas em SQL. Obrigado por assistir!"

------

### 📦 Entrega Final

- ✅ Documento textual (.docx/.pdf)
- ✅ Apresentação (.pptx/.pdf)
- ✅ Pasta compactada com SQL + DER
- ✅ Link para vídeo gravado (Google Drive, Loom, YouTube não listado)

------

### 🧩 Ferramentas Recomendadas

| Tarefa             | Ferramenta                                    |
| ------------------ | --------------------------------------------- |
| Modelagem ER       | MySQL Workbench, dbdiagram.io, Draw.io        |
| Criação de banco   | MySQL, DBeaver, VSCode (com extensão SQL)     |
| Gravação de vídeo  | OBS Studio, Loom, gravador de tela nativo     |
| Documento e slides | Google Docs / Slides, LibreOffice, PowerPoint |

------

## ✅ **Modelo ER (Entidade-Relacionamento)**

```markdown
## 📘 Dicionário de Dados – UC16

| Tabela     | Campo      | Tipo           | Descrição                           | Restrição            |
|------------|------------|----------------|-------------------------------------|----------------------|
| alunos     | id         | INT            | Identificador único do aluno        | PK                   |
| alunos     | nome       | VARCHAR(100)   | Nome completo do aluno              |                      |
| alunos     | matricula  | VARCHAR(20)    | Código de matrícula do aluno        | UNIQUE               |
| turmas     | id         | INT            | Identificador único da turma        | PK                   |
| turmas     | nome       | VARCHAR(50)    | Nome da turma                       |                      |
| turmas     | ano        | YEAR           | Ano letivo da turma                 |                      |
| disciplinas| id         | INT            | Identificador único da disciplina   | PK                   |
| disciplinas| nome       | VARCHAR(100)   | Nome da disciplina                  |                      |
| chamadas   | id         | INT            | Identificador da chamada            | PK                   |
| chamadas   | data       | DATE           | Data da chamada                     |                      |
| chamadas   | presenca   | BOOLEAN        | Presença ou ausência do aluno       |                      |
| chamadas   | aluno_id   | INT            | Referência ao aluno                 | FK → alunos(id)      |
| chamadas   | turma_id   | INT            | Referência à turma                  | FK → turmas(id)      |

```

📌 **Diagrama ER:**

![](/home/alunotec/Documents/compensacao-ausencias/er_uc16_escola.png)

