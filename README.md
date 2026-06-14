# 🎨 Portfólio - Renato Cirilo

Bem-vindo ao meu portfólio profissional! Este é um site moderno e responsivo para apresentar meus trabalhos, projetos e habilidades.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Recursos](#recursos)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Usar](#como-usar)
- [Personalização](#personalização)
- [Deploy no GitHub Pages](#deploy-no-github-pages)
- [Tecnologias](#tecnologias)

## 🎯 Sobre o Projeto

Este portfólio foi criado para apresentar profissionalmente meus projetos, habilidades e informações de contato. É uma aplicação web moderna, responsiva e totalmente funcional.

## ✨ Recursos

- ✅ Design moderno e responsivo
- ✅ Seções: Início, Sobre, Projetos, Habilidades, Contato
- ✅ Navegação suave (smooth scrolling)
- ✅ Menu responsivo para dispositivos móveis
- ✅ Animações de entrada elegantes
- ✅ Gradientes visuais atraentes
- ✅ Ícones Font Awesome
- ✅ Totalmente otimizado para SEO

## 📁 Estrutura do Projeto

```
Renato-Cirilo-/
├── index.html      # Página principal (HTML)
├── styles.css      # Estilos (CSS)
├── script.js       # Funcionalidades (JavaScript)
├── README.md       # Este arquivo
└── .gitignore      # Arquivos ignorados pelo Git
```

## 🚀 Como Usar

### 1. Clonar o Repositório

```bash
git clone https://github.com/renatoafk/Renato-Cirilo-.git
cd Renato-Cirilo-
```

### 2. Abrir Localmente

Abra o arquivo `index.html` em seu navegador:

- **Windows/Linux**: Clique duas vezes no arquivo `index.html`
- **macOS**: Arraste o arquivo para o navegador ou clique duas vezes

Ou use um servidor local:

```bash
# Com Python 3
python -m http.server 8000

# Com Python 2
python -m SimpleHTTPServer 8000

# Com Node.js (live-server)
npx live-server
```

Então acesse: `http://localhost:8000`

## 🎨 Personalização

### Editar Informações Pessoais

Abra o arquivo `index.html` e procure pelas seguintes seções:

1. **Nome e Profissão** (Hero Section)
   ```html
   <h1>Olá! Eu sou <span class="highlight">SEU_NOME</span></h1>
   <p class="subtitle">SUA_PROFISSÃO | OUTRO | OUTRO</p>
   ```

2. **Email e Contato** (Contact Section)
   ```html
   <a href="mailto:seu.email@example.com">
   ```

3. **Links Sociais**
   ```html
   <a href="https://github.com/seu-usuario" target="_blank">
   <a href="https://linkedin.com/in/seu-perfil" target="_blank">
   ```

### Editar Projetos

Procure pela seção de projetos e modifique:

```html
<div class="project-card">
    <h3>Nome do Projeto</h3>
    <p>Descrição do seu projeto</p>
    <div class="project-tags">
        <span class="tag">Tecnologia1</span>
        <span class="tag">Tecnologia2</span>
    </div>
    <a href="https://seu-link.com">Ver Projeto</a>
</div>
```

### Mudar Cores

Edite o arquivo `styles.css` e procure pelas cores das variáveis no topo:

```css
:root {
    --primary-color: #6c5ce7;      /* Cor primária */
    --secondary-color: #00b894;    /* Cor secundária */
    --dark-color: #2d3436;         /* Cor escura */
    --light-color: #f5f6fa;        /* Cor clara */
    --text-color: #2d3436;         /* Cor do texto */
}
```

## 📤 Deploy no GitHub Pages

### Passo 1: Configurar GitHub Pages

1. Vá para as configurações do repositório
2. Desça até a seção **Pages**
3. Em "Build and deployment", selecione:
   - **Source**: Deploy from a branch
   - **Branch**: main (ou sua branch padrão)
   - **Folder**: / (root)
4. Clique em Save

### Passo 2: Acessar seu Site

Após alguns minutos, seu site estará disponível em:

```
https://renatoafk.github.io/Renato-Cirilo-/
```

## 🛠 Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos e responsivos
- **JavaScript (Vanilla)** - Interatividade
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia

## 📝 Dicas Extras

### Adicionar Favicon

```html
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

### Adicionar Google Analytics

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXX-X"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-XXXXXXXX-X');
</script>
```

### Adicionar Meta Descrição

```html
<meta name="description" content="Seu portfólio profissional com projetos e habilidades">
```

## 💡 Próximos Passos

- [ ] Adicionar fotos dos projetos
- [ ] Criar página de blog
- [ ] Adicionar formulário de contato funcional
- [ ] Integrar com CMS
- [ ] Melhorar SEO

## 📞 Contato

- 📧 Email: seu.email@example.com
- 💼 LinkedIn: linkedin.com/in/renatoafk
- 🐙 GitHub: github.com/renatoafk
- 🐦 Twitter: @renatoafk

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo LICENSE para detalhes.

---

**Feito com ❤️ por Renato Cirilo**
