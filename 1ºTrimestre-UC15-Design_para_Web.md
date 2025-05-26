## 🎓 Trabalho de Compensação – UC15: Design para Web

**Curso:** Ensino Médio Técnico em Informática
 **Aluno:** [Nome do Aluno]
 **Turma:** [3ºC]
 **Professor:** André Ricardo da Silva
 **Entrega até:** [Definir data]

------

### 📁 Estrutura do Trabalho

O trabalho será dividido em **quatro partes integradas**:

------

### **Parte 1 – Documento Textual (.docx ou .pdf)**

#### 📄 Tema: **Fundamentos e Práticas em Design para Web**

#### 📌 Estrutura Sugerida:

1. **Introdução**
   - O que é Design para Web e sua importância.
2. **HTML – Conceitos e Estrutura**
   - Breve explicação sobre HTML.
   - Versões mais usadas e diferenças.
   - Principais elementos: `<head>`, `<body>`, `<header>`, `<footer>`, etc.
   - Estruturas de listas, imagens, formulários e scripts.
   - Semântica e acessibilidade no HTML5.
   - Princípios de SEO básico.
3. **CSS – Conceitos e Aplicações**
   - O que é CSS e como evoluiu (CSS1, CSS2, CSS3).
   - Diferença entre CSS interno, externo e inline.
   - Seletores, atributos e unidades de medida.
   - Modelo de caixa e layout (fixo, fluido, flex, grid).
   - Compatibilidade e boas práticas.
4. **Comunicação Visual para Web**
   - Conceitos de imagem digital, cores, vetores e bitmaps.
   - Tipografia, resolução, modo de cor.
   - Princípios de composição visual (grid, camadas, harmonia de cores).
   - Otimização e exportação de imagens para web.
   - Protótipos, wireframes e leiaute.
5. **Conclusão**
   - O que foi aprendido e como o conhecimento será aplicado em projetos futuros.

------

### **Parte 2 – Apresentação (.pptx ou .pdf)**

#### 🎤 Tema: **Boas Práticas em HTML, CSS e Design Visual para Web**

- Slide 1: Capa com título, nome, turma, disciplina.
- Slide 2: Estrutura básica de uma página HTML.
- Slide 3: Modelos de formulários e listas.
- Slide 4: Introdução ao CSS e seus tipos.
- Slide 5: Seletores, atributos e layout.
- Slide 6: Comunicação visual – imagem digital e tipografia.
- Slide 7: Teoria das cores e exemplos de composição.
- Slide 8: Ferramentas utilizadas (Figma, GIMP, Canva, VSCode etc.)
- Slide 9: Protótipo criado (tela capturada da atividade prática).
- Slide 10: Considerações finais e aprendizados.

------

### **Parte 3 – Atividade Prática (código HTML + CSS + imagem)**

#### 💻 Desafio: **Criar uma Página Web Pessoal Simples**

- Criar uma página chamada `index.html`, com:
  - Cabeçalho com nome e breve biografia.
  - Foto de perfil (imagem embutida).
  - Lista de hobbies (lista ordenada e não ordenada).
  - Um formulário de contato.
  - Aplicar CSS externo com:
    - Layout centralizado.
    - Estilização de texto e listas.
    - Uso de cores, fontes, espaçamento e imagens de fundo.
    - Responsividade simples (media queries básicas).
- Criar um **wireframe ou protótipo visual simples** do site (pode ser feito no Canva, Figma ou desenhado à mão e digitalizado).
- Salvar tudo em uma pasta zipada com o nome: `trabalho_uc15_nome.zip`

------

### **Parte 4 – Vídeo Explicativo (2 a 5 minutos)**

#### 🎬 Conteúdo do vídeo:

- Gravação da tela com o aluno explicando:
  - A estrutura do código HTML e CSS.
  - Como pensou o layout e o design visual.
  - As imagens e cores escolhidas.
  - Demonstração da página funcionando no navegador.
- O aluno pode usar ferramentas como OBS Studio, Loom, Zoom ou mesmo o gravador de tela do celular com narração.

------

### 📦 Entrega Final

#### A entrega deverá conter:

- ✅ Documento em .docx ou .pdf (parte 1).
- ✅ Apresentação em .pptx ou .pdf (parte 2).
- ✅ Pasta compactada com os arquivos HTML, CSS e imagens (parte 3).
- ✅ Link para o vídeo (pode ser enviado via Google Drive, YouTube não listado ou WeTransfer).

------

### 🧩 Sugestões de Ferramentas

| Tipo                  | Ferramenta Recomendada               |
| --------------------- | ------------------------------------ |
| Editor de código      | VSCode, Notepad++, Sublime           |
| Prototipação          | Figma, Canva, Pencil, papel e caneta |
| Imagem e edição       | GIMP, Photopea, Krita                |
| Gravação de vídeo     | OBS Studio, Loom, Screencast-O-Matic |
| Exportação/Compressão | WinRAR, 7zip ou zip nativo do SO     |

------

### 💡 Observações Finais

- Capriche na identidade visual: cores, alinhamento, fontes.
- Use comentários no código para mostrar que entendeu cada parte.
- Siga boas práticas e referências aprendidas nas aulas.
- Se quiser, insira recursos extras como CSS Grid, Flexbox, animações simples, ícones com Font Awesome etc.

------

# Template de Roteiro e Arquivos Base

Perfeito! Abaixo estão os **modelos de arquivos base** e um **roteiro detalhado para o vídeo explicativo**, conforme solicitado:

------

## 📁 **Modelos de Arquivo Base – Trabalho UC15**

------

### 📝 1. `index.html` (modelo base)

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Página pessoal de [Seu Nome]">
  <title>Página Pessoal – [Seu Nome]</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Olá, eu sou [Seu Nome]</h1>
    <p>Estudante do Ensino Médio Técnico em Informática</p>
  </header>

  <section class="perfil">
    <img src="img/foto-perfil.jpg" alt="Foto de [Seu Nome]">
    <p>Tenho interesse em tecnologia, design e desenvolvimento web.</p>
  </section>

  <section class="hobbies">
    <h2>🎯 Meus Hobbies</h2>
    <ol>
      <li>Programar</li>
      <li>Jogar videogame</li>
      <li>Assistir séries</li>
    </ol>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Design Gráfico</li>
    </ul>
  </section>

  <section class="contato">
    <h2>📩 Fale comigo</h2>
    <form>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>

      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2025 – Desenvolvido por [Seu Nome]</p>
  </footer>
</body>
</html>
```

------

### 🎨 2. `style.css` (modelo base)

```css
/* Reset e configurações globais */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
  padding: 20px;
  max-width: 800px;
  margin: auto;
}

/* Cabeçalho */
header {
  background-color: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
}

/* Perfil */
.perfil {
  margin: 20px 0;
  text-align: center;
}

.perfil img {
  width: 150px;
  border-radius: 50%;
  margin-bottom: 10px;
}

/* Hobbies */
.hobbies {
  background-color: #fff;
  padding: 15px;
  margin-bottom: 20px;
  border-radius: 8px;
}

/* Contato */
form {
  display: flex;
  flex-direction: column;
}

form label,
form input,
form textarea {
  margin-bottom: 10px;
}

input, textarea {
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background-color: #0077cc;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

/* Rodapé */
footer {
  text-align: center;
  font-size: 0.9em;
  margin-top: 30px;
}

/* Responsivo */
@media (max-width: 600px) {
  body {
    padding: 10px;
  }

  .perfil img {
    width: 100px;
  }
}
```

------

### 🖼️ 3. Imagem de Perfil

- Crie uma pasta `img/` e adicione uma imagem com o nome `foto-perfil.jpg` (ou outra que preferir).
- A imagem pode ser sua ou uma imagem representativa.

------

### 📜 4. Roteiro para o Vídeo Explicativo (2 a 5 minutos)

#### 🎥 Sugestão de fala e ordem de apresentação:

------

### 🎬 **Introdução**

**Duração:** 20–30 segundos
 **Fala:**
 "Olá! Eu sou [Seu Nome], aluno do 3º ano Técnico em Informática, e esse é meu trabalho de compensação da UC15 – Design para Web. Neste vídeo, vou mostrar como desenvolvi minha página web usando HTML, CSS e conceitos de design visual para web."

------

### 🧱 **Explicação do HTML**

**Duração:** 1 minuto
 **Fala:**
 "Comecei criando a estrutura do HTML com a declaração `<!DOCTYPE html>` e defini o idioma da página como português. No `<head>`, coloquei a codificação UTF-8, título, descrição e linkei o CSS externo.
 No corpo da página, usei elementos semânticos como `<header>`, `<section>`, `<footer>`, e também criei listas e um formulário com os campos de nome, e-mail e mensagem. Utilizei elementos como `input`, `textarea` e `button`."

------

### 🎨 **Explicação do CSS**

**Duração:** 1 minuto
 **Fala:**
 "Na folha de estilo `style.css`, comecei com um reset global e defini cores, fontes e espaçamento para deixar a página agradável. Usei seletores de tag, classe e ID.
 Configurei o layout para ser responsivo com media queries e organizei as seções usando margem, padding e bordas arredondadas. Também utilizei estilização nos botões e nos formulários para melhorar a usabilidade."

------

### 🧠 **Conceitos de Design e Comunicação Visual**

**Duração:** 1 minuto
 **Fala:**
 "Na escolha das cores, usei uma paleta com azul para transmitir confiança. A tipografia foi pensada para garantir boa leitura.
 Também me preocupei com contraste e hierarquia visual. A imagem do perfil foi redimensionada e otimizada para a web, e o layout foi pensado com base em grids e organização de conteúdo."

------

### ✅ **Demonstração Final**

**Duração:** 30–60 segundos
 **Fala:**
 "Agora vou mostrar a página funcionando no navegador. (Mostre o código e o resultado ao vivo.)
 Podemos ver o cabeçalho, a imagem do perfil, a lista de hobbies e o formulário.
 A página funciona bem em celulares e desktops."

------

### 🧾 **Encerramento**

**Duração:** 10–15 segundos
 **Fala:**
 "Esse foi meu trabalho de compensação da UC15. Espero que tenham gostado. Obrigado!"

------

