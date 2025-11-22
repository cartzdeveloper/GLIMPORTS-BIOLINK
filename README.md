# 💎 GL Imports - Premium Store | Link in Bio

> **"O Padrão Ouro em Tecnologia & Games Exclusivos"**

Bem-vindo ao repositório oficial da página "Link in Bio" da **GL Imports**. Este projeto foi desenvolvido para oferecer uma experiência digital de alto padrão, alinhada com a exclusividade dos produtos comercializados (iPhones, Xiaomi, PS5, JBL).

O site funciona como um cartão de visita digital interativo, focado em conversão via WhatsApp e fortalecimento da marca.

---

## ✨ Identidade Visual & Design

O design foi meticulosamente trabalhado para transmitir luxo, sofisticação e modernidade.

-   **Paleta de Cores:** `Black Piano` (#050505) como base, com acentos em `Gold Gradient` (#D4AF37) para evocar riqueza e exclusividade.
-   **Tipografia:** Utilização da família **Montserrat**, uma fonte geométrica sans-serif que equilibra modernidade e legibilidade.
-   **Glassmorphism:** Os cartões utilizam um efeito de vidro fosco (blur) com bordas douradas sutis, criando profundidade sobre o fundo texturizado.
-   **Loading Screen Exclusivo:** Uma introdução cinematográfica que apresenta as principais marcas (Apple, JBL, Xiaomi) com efeitos de pulsação e filtros dourados antes de revelar o conteúdo principal.

---

## 🚀 Funcionalidades

1.  **Preloader de Marcas:**
    -   Animação sequencial exibindo os logotipos das marcas parceiras.
    -   Filtro CSS inteligente que uniformiza logotipos de diferentes cores (Preto ou Laranja) para um padrão Branco/Dourado luxuoso.
    
2.  **Links Inteligentes:**
    -   **WhatsApp (Principal):** Botão de destaque com gradiente dourado sólido para máxima conversão (CTA).
    -   **Nossa História & Localização:** Botões secundários com estilo "Dark Glass" para informações complementares.
    
3.  **Modal "Sobre Nós":**
    -   Uma janela modal elegante que conta a história da loja sem que o usuário precise sair da página principal.
    
4.  **Responsividade Total:**
    -   Layout fluido que se adapta perfeitamente a iPhones, Androids, Tablets e Desktops.

---

## 🛠️ Tecnologias

Este projeto utiliza uma arquitetura **Serverless Frontend** extremamente leve:

-   **HTML5** (Estrutura Semântica)
-   **Tailwind CSS** (Estilização Utility-First via CDN)
-   **React.js** (Renderização de componentes via CDN)
-   **Babel** (Transpilação JSX em tempo real)

*Não é necessário instalação de Node.js ou processos de build (npm/yarn) para editar ou rodar este projeto.*

---

## 📦 Como Usar / Editar

Basta baixar o arquivo `index.html` e abri-lo em seu navegador ou editor de código.

### Personalização Rápida

No final do arquivo `index.html`, dentro da tag `<script type="text/babel">`, você encontrará as variáveis para fácil edição:

**1. Alterar Links (WhatsApp, Mapas, etc):**
Procure pela constante `mainLinks`:
```javascript
const mainLinks = [
  {
    id: 'whatsapp',
    text: 'Atendimento via Whatsapp',
    url: 'https://wa.me/5500000000000', // Seu número aqui
    // ...
  },
  // ...
];
```

**2. Alterar Marcas do Loading:**
Procure pela constante `brands` dentro do componente `LoadingScreen`:
```javascript
const brands = [
  { 
    id: 'apple', 
    label: 'APPLE', 
    // ...
  },
  // ...
];
```

**3. Alterar Texto "Sobre Nós":**
Edite o conteúdo HTML dentro do componente `AboutModal`.

---

## 🌐 Deploy (Como colocar no ar)

Por ser um arquivo único, você pode hospedar gratuitamente em:

1.  **Vercel / Netlify:** Arraste a pasta contendo o `index.html`.
2.  **GitHub Pages:** Habilite o Pages nas configurações do repositório.
3.  **Hospedagem Comum:** Upload via FTP para a pasta `public_html`.

---

<div align="center">

**Desenvolvido por Hyper Tech**  
*Elevando seu negócio ao próximo nível.*

</div>