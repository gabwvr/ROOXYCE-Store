# ROOXYCE Store - E-commerce de Eletrônicos

## 📋 Sobre o Projeto

ROOXYCE Store é um e-commerce moderno especializado em eletrônicos, desenvolvido com HTML, CSS e JavaScript puro. O projeto conta com design responsivo, identidade visual em roxo e amarelo, e funcionalidades completas de loja online.

## ✨ Funcionalidades

### 🛒 E-commerce
- Catálogo de produtos com filtros avançados
- Sistema de carrinho de compras
- Lista de desejos
- Sistema de busca com sugestões
- Páginas de produto detalhadas
- Processo de checkout completo

### 👤 Usuário
- Sistema de login e cadastro
- Painel do usuário com dashboard
- Histórico de pedidos
- Gerenciamento de endereços
- Sistema de XP e gamificação

### 🎨 Design
- Design responsivo para todos os dispositivos
- Identidade visual moderna (roxo #7c3aed e amarelo #eab308)
- Animações e transições suaves
- Tema escuro disponível
- Interface intuitiva e acessível

### 📱 Responsividade
- Mobile-first design
- Breakpoints otimizados:
  - Mobile: até 480px
  - Mobile Large: 481px - 768px
  - Tablet: 769px - 1024px
  - Desktop: 1025px+

## 🚀 Deploy no Vercel

### Pré-requisitos
- Conta no [Vercel](https://vercel.com)
- Git instalado

### Passos para Deploy

1. **Preparar o projeto:**
   ```bash
   # O projeto já está preparado com vercel.json configurado
   ```

2. **Deploy via Vercel CLI:**
   ```bash
   npm i -g vercel
   vercel --prod
   ```

3. **Deploy via GitHub:**
   - Faça push do código para um repositório GitHub
   - Conecte o repositório no painel do Vercel
   - O deploy será automático

4. **Deploy via Dashboard:**
   - Acesse [vercel.com](https://vercel.com)
   - Clique em "New Project"
   - Faça upload da pasta do projeto
   - Configure o nome do projeto
   - Clique em "Deploy"

### Configurações do Vercel

O arquivo `vercel.json` já está configurado com:
- Rotas personalizadas
- Headers de segurança
- Cache otimizado para assets
- Redirecionamentos

## 📁 Estrutura do Projeto

```
src/
├── css/                    # Arquivos de estilo
│   ├── cabecalhorodape.css # Estilos do cabeçalho e rodapé
│   ├── home.css           # Estilos da página inicial
│   ├── produtos.css       # Estilos da página de produtos
│   ├── painelusuario.css  # Estilos do painel do usuário
│   ├── painel-melhorado.css # Melhorias do painel
│   └── responsivo.css     # CSS responsivo
├── js/                    # Scripts JavaScript
│   ├── database.js        # Base de dados dos produtos
│   ├── home.js           # Funcionalidades da home
│   ├── carrinho.js       # Sistema de carrinho
│   ├── cabecalhorodape.js # Funcionalidades do cabeçalho
│   └── cabecalho-melhorado.js # Melhorias do cabeçalho
├── images/               # Imagens do sistema
│   ├── logo-rooxyce.png  # Logo da loja
│   └── favicon-rooxyce.png # Favicon
├── imagens/              # Imagens de produtos e banners
├── videos/               # Vídeos promocionais
├── *.html               # Páginas HTML
├── vercel.json          # Configuração do Vercel
└── README.md            # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e responsividade
- **JavaScript ES6+** - Funcionalidades interativas
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia (Nunito Sans)

## 🎯 Melhorias Implementadas

### ✅ Correções de Layout
- Centralização da caixa de pesquisa
- Centralização do ícone do carrinho
- Alinhamento do breadcrumb com o banner
- Correção do alinhamento do rodapé

### ✅ Correções de CSS
- Painel do usuário otimizado
- Barra de categorias com cores alinhadas
- Rodapé responsivo e bem estruturado

### ✅ Funcionalidades
- Links de categorias funcionais
- Produtos aparecem na página inicial
- Botões de compra e carrinho em todos os cards
- Sistema de navegação melhorado

### ✅ Elementos Visuais
- Vídeo promocional na home page
- Logo implementada corretamente
- Favicon em todas as páginas

### ✅ Responsividade
- 100% mobile-friendly
- Breakpoints otimizados
- Touch-friendly em dispositivos móveis
- Orientação landscape suportada

## 🔧 Configurações de Desenvolvimento

### Servidor Local
Para testar localmente, use qualquer servidor HTTP:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

### Estrutura de URLs
- `/` ou `/home` → home.html
- `/produtos` → produtos.html
- `/carrinho` → carrinho.html
- `/login` → login.html
- `/painel` → painelusuario.html

## 📞 Suporte

Para suporte técnico ou dúvidas sobre o projeto, entre em contato através da página de contato da loja.

## 📄 Licença

Este projeto foi desenvolvido por Gabriel (gabwvr) para a ROOXYCE Store.

---

**ROOXYCE Store** - Os melhores preços em eletrônicos! 🚀

