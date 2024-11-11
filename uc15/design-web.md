# 🎨 PROJETO PRÁTICO: REDESIGN DE INTERFACE (60%)

## Sua Missão
Escolha uma rede social (Instagram, TikTok, Twitter, etc.) e faça um redesign moderno de suas principais telas!

### FASE 1: Planejamento (20 pontos)

1. **Análise do Design Atual**
   - Pontos fortes e fracos
   - O que pode melhorar
   - Público-alvo
   - Tendências atuais

2. **Style Guide**
   ```css
   /* Exemplo de Documentação */
   :root {
       /* Cores principais */
       --primary-color: #yourcolor;
       --secondary-color: #yourcolor;
       --accent-color: #yourcolor;
       
       /* Tipografia */
       --heading-font: 'Your Font', sans-serif;
       --body-font: 'Your Font', sans-serif;
       
       /* Espaçamentos */
       --spacing-sm: 0.5rem;
       --spacing-md: 1rem;
       --spacing-lg: 2rem;
   }
   ```

### FASE 2: Implementação (40 pontos)

1. **HTML Estruturado**
```html
<!-- Estrutura Semântica -->
<header class="app-header">
    <nav class="main-nav">
        <!-- Navegação -->
    </nav>
</header>

<main class="feed-container">
    <section class="stories">
        <!-- Stories -->
    </section>
    
    <section class="posts">
        <!-- Posts -->
    </section>
</main>

<footer class="app-footer">
    <!-- Footer -->
</footer>
```

2. **CSS Moderno**
```css
/* Design System */
.layout-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-md);
}

/* Componentes */
.card {
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s ease;
}

/* Responsividade */
@media (max-width: 768px) {
    /* Ajustes mobile */
}
```

3. **Interatividade com JavaScript**
```javascript
// Exemplos de funcionalidades
const toggleTheme = () => {
    document.body.classList.toggle('dark-mode');
}

const handleLike = (postId) => {
    // Animação de like
}
```

## Telas Obrigatórias

1. **Header/Navegação**
   - Logo
   - Menu principal
   - Busca
   - Perfil

2. **Feed Principal**
   - Stories/Destaques
   - Posts/Conteúdo
   - Interações

3. **Perfil do Usuário**
   - Info do perfil
   - Grid de conteúdo
   - Estatísticas

## ⭐ Pontos Extras! (10 pontos)
- Animações suaves
- Dark/Light mode
- Micro-interações
- Layout alternativo
