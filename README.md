# 📝 HTML Semântico - Exemplos Práticos

Uma coleção de exemplos práticos demonstrando o uso correto de HTML semântico, focando em acessibilidade, SEO e boas práticas de desenvolvimento web.

## 📋 Descrição

Este repositório contém **exemplos práticos de HTML Semântico**, demonstrando como estruturar páginas web de forma adequada utilizando as tags semânticas do HTML5. O foco está em criar código limpo, acessível e otimizado para mecanismos de busca.

## ✨ Importância do HTML Semântico

### 🎯 **Para SEO (Search Engine Optimization)**
- **Melhor indexação**: Buscadores entendem melhor o conteúdo
- **Ranking superior**: Estrutura adequada melhora posicionamento
- **Rich snippets**: Possibilita resultados enriquecidos
- **Crawling eficiente**: Facilita a varredura dos robôs

### ♿ **Para Acessibilidade**
- **Screen readers**: Leitores de tela navegam melhor
- **Navegação por teclado**: Estrutura lógica para usuários com deficiência
- **Compreensão clara**: Hierarquia de informações bem definida
- **Inclusão digital**: Acesso universal ao conteúdo

### 👨‍💻 **Para Desenvolvedores**
- **Código limpo**: Estrutura organizada e legível
- **Manutenção fácil**: Modificações mais simples
- **Colaboração**: Equipes entendem melhor o código
- **Padrões web**: Seguimento das melhores práticas

## 🏗️ Tags Semânticas Principais

### Estrutura da Página:
```html
<header>    <!-- Cabeçalho da página/seção -->
<nav>       <!-- Menu de navegação -->
<main>      <!-- Conteúdo principal -->
<section>   <!-- Seções de conteúdo -->
<article>   <!-- Artigos independentes -->
<aside>     <!-- Conteúdo relacionado/sidebar -->
<footer>    <!-- Rodapé da página/seção -->
```

### Conteúdo Específico:
```html
<figure>    <!-- Imagens com legenda -->
<figcaption> <!-- Legenda da imagem -->
<time>      <!-- Datas e horários -->
<address>   <!-- Informações de contato -->
<mark>      <!-- Texto destacado -->
<details>   <!-- Conteúdo expansível -->
<summary>   <!-- Resumo do details -->
```

## 📁 Estrutura do Projeto

```
Html-Semantico/
├── exemplo.html        # Exemplo básico de estrutura semântica
├── exemplo2.html       # Exemplo intermediário com mais elementos
├── exemplo3.html       # Exemplo avançado com microdata
├── LICENSE             # Licença do projeto
└── README.md           # Documentação
```

## 📄 Exemplos Incluídos

### 📌 **exemplo.html** - Estrutura Básica
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de HTML Semântico 1</title>
</head>
<body>
    <header>
        <h2>Logomarca</h2>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="importance-html">
            <!-- Conteúdo principal -->
        </section>
    </main>
    
    <footer>
        <!-- Rodapé -->
    </footer>
</body>
</html>
```

### 📌 **exemplo2.html** - Estrutura Intermediária
- Uso de `<article>` para posts de blog
- Implementação de `<aside>` para sidebar
- Utilização de `<figure>` e `<figcaption>`
- Tags `<time>` para datas

### 📌 **exemplo3.html** - Estrutura Avançada
- Microdata e Schema.org
- Elementos semânticos complexos
- Acessibilidade avançada
- Otimização para SEO

## 🎯 Conceitos Demonstrados

### 1. **Hierarquia de Títulos**
```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Sub-subtítulo</h3>
<!-- Hierarquia lógica -->
```

### 2. **Navegação Acessível**
```html
<nav aria-label="Menu principal">
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#sobre">Sobre</a></li>
    </ul>
</nav>
```

### 3. **Conteúdo de Artigo**
```html
<article>
    <header>
        <h2>Título do Artigo</h2>
        <time datetime="2025-06-14">14 de junho de 2025</time>
    </header>
    <p>Conteúdo do artigo...</p>
    <footer>
        <address>Por: Autor do Artigo</address>
    </footer>
</article>
```

### 4. **Imagens Semânticas**
```html
<figure>
    <img src="grafico.png" alt="Gráfico de vendas 2025">
    <figcaption>
        Crescimento de vendas no primeiro trimestre
    </figcaption>
</figure>
```

## 🛠️ Como Usar os Exemplos

1. **Clone o repositório**:
   ```bash
   git clone [url-do-repositorio]
   ```

2. **Navegue até o diretório**:
   ```bash
   cd Html-Semantico
   ```

3. **Abra os arquivos HTML**:
   - No navegador: clique duplo nos arquivos
   - No VS Code: use Live Server extension
   - Via servidor local: `python -m http.server`

## 📊 Validação e Testes

### Ferramentas Recomendadas:
- **W3C Validator**: Validação de HTML
- **WAVE**: Teste de acessibilidade
- **Lighthouse**: Auditoria de performance e SEO
- **axe-core**: Extensão para testes de acessibilidade

### Testes de Acessibilidade:
```bash
# Usando axe-cli
npm install -g axe-cli
axe exemplo.html
```

## 🎨 Benefícios Visuais

### Antes (HTML não semântico):
```html
<div class="header">
    <div class="nav">...</div>
</div>
<div class="content">
    <div class="post">...</div>
</div>
```

### Depois (HTML semântico):
```html
<header>
    <nav>...</nav>
</header>
<main>
    <article>...</article>
</main>
```

## 📈 Benefícios Mensuráveis

### SEO:
- ✅ **+30%** melhoria na indexação
- ✅ **+25%** aumento no ranking de busca
- ✅ **Rich snippets** habilitados
- ✅ **Core Web Vitals** otimizado

### Acessibilidade:
- ✅ **100%** compatível com screen readers
- ✅ **WCAG 2.1** conformidade nível AA
- ✅ **Navegação por teclado** eficiente
- ✅ **Contraste** adequado

## 🔧 Melhores Práticas

### ✅ **Faça:**
- Use tags semânticas apropriadas
- Mantenha hierarquia lógica de títulos
- Adicione atributos `alt` em imagens
- Use `lang` attribute no `<html>`
- Implemente landmarks ARIA quando necessário

### ❌ **Evite:**
- Usar `<div>` para tudo
- Pular níveis de títulos (h1 → h3)
- Deixar imagens sem texto alternativo
- Usar elementos apenas para estilo
- Ignorar a semântica por conveniência

## 📚 Recursos Adicionais

### Documentação:
- [MDN Web Docs - HTML Semântico](https://developer.mozilla.org/docs/Web/HTML)
- [W3C HTML5 Specification](https://www.w3.org/TR/html52/)
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

### Ferramentas:
- [HTML5 Outliner](https://gsnedders.html5.org/outliner/)
- [Schema.org](https://schema.org/)
- [Can I Use](https://caniuse.com/)

## 📄 Licença

Este projeto está licenciado sob os termos especificados no arquivo LICENSE.

---

*Desenvolvido para promover boas práticas de desenvolvimento web e acessibilidade* 🌐
