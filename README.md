
# Fernando Barbershop - Página de Links (Link in Bio)



Uma página de links no estilo "link-in-bio" elegante, moderna e totalmente responsiva, criada para a **Fernando Barbershop**. Este projeto consolida todos os links importantes da barbearia em uma única página de destino, otimizada para dispositivos móveis e com uma identidade visual premium que reflete a qualidade da marca.

O site foi construído como um único arquivo HTML autocontido, utilizando React e Tailwind CSS via CDN, o que o torna extremamente portátil e fácil de implantar em qualquer serviço de hospedagem estática.

---

## ✨ Funcionalidades

- **Design Unificado:** Todo o conteúdo é apresentado em um único "cartão de visita" digital, com efeito de vidro fosco (frosted glass) e uma sutil textura granulada para uma aparência sofisticada.
- **Totalmente Responsivo:** O layout se adapta perfeitamente a desktops, tablets e smartphones.
- **Interatividade:**
    - Botões com efeitos de *hover* e *focus* polidos para uma melhor experiência do usuário.
    - Modal "Quem Somos?" que abre suavemente para exibir mais informações sobre a barbearia.
- **Otimizado para Compartilhamento (SEO & Social):**
    - **Favicon:** Ícone da marca na aba do navegador.
    - **Meta Tags (Open Graph):** Garante uma pré-visualização rica e profissional ao compartilhar o link no WhatsApp, Instagram, Facebook e outras redes sociais.
- **Tipografia Profissional:** Utiliza as fontes *Bebas Neue* para títulos e *Roboto* para o corpo do texto, garantindo legibilidade e estilo.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com tecnologias web modernas, mas de uma forma que elimina a necessidade de um processo de build complexo.

- **HTML5:** Estrutura semântica do conteúdo.
- **CSS3 & Tailwind CSS (via CDN):** Estilização rápida e responsiva. Estilos personalizados foram adicionados para efeitos específicos.
- **JavaScript (ES6+):** Lógica e interatividade.
- **React (via CDN):** A interface do usuário é construída como uma aplicação React, renderizada diretamente no navegador.
- **Babel (via CDN):** Utilizado para transpilar o código JSX em tempo real no navegador.
- **Google Fonts:** Para carregar as fontes personalizadas `Bebas Neue` e `Roboto`.

---

## 🚀 Como Executar

A grande vantagem deste projeto é sua simplicidade.

1.  **Faça o download do arquivo `index.html`.**
2.  **Abra o arquivo em qualquer navegador web moderno.**

É isso! Não há necessidade de instalar dependências ou executar um servidor de desenvolvimento.

Para publicar o site, basta fazer o upload do arquivo `index.html` para qualquer serviço de hospedagem de sites estáticos, como:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

---

## 🎨 Como Personalizar

Toda a lógica e conteúdo do site estão dentro do arquivo `index.html`. Para fazer alterações, abra o arquivo em um editor de código e navegue até a tag `<script type="text/babel">`.

-   **Alterar Links Principais:** Modifique o array `mainLinks`. Você pode alterar textos, URLs e ícones.
    ```javascript
    const mainLinks = [
      {
        id: 'schedule',
        text: 'NOVO TEXTO DO BOTÃO',
        url: 'https://seu-novo-link.com',
        // ...
      },
      // ...
    ];
    ```

-   **Alterar Links de Redes Sociais:** Encontre a seção `<footer>` e altere o `href` da tag `<a>`.
    ```jsx
    <a href="https://instagram.com/seu-usuario" target="_blank" ...>
      <InstagramIcon ... />
    </a>
    ```

-   **Alterar Imagens:** Substitua as URLs do logo e da imagem de fundo.
    ```jsx
    // Imagem de fundo (no componente App)
    <div style={{ backgroundImage: "url('https://nova-imagem-de-fundo.jpg')" }}>...</div>

    // Logo (no componente App)
    <img src="https://novo-logo.jpeg" ... />
    ```

-   **Alterar Textos:** Edite diretamente o conteúdo de texto dentro dos componentes JSX, como o título (`<h1>`), a descrição (`<p>`) ou o conteúdo do modal `AboutModal`.

---

Desenvolvido com ❤️ por [Hyper Tech](https://www.hyper-tech.online/).
