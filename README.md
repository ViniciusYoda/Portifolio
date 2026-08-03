# Portfólio — Vinícius Yoda

Portfólio profissional de Vinícius Yoda, desenvolvedor Full Stack. O site apresenta minha experiência, principais tecnologias e canais de contato em uma interface responsiva e acessível.

## Visão geral

O projeto foi construído como um site estático, sem frameworks ou etapa de compilação. Isso torna a execução simples e permite publicá-lo em qualquer serviço compatível com HTML e CSS.

O conteúdo está dividido em duas páginas:

- **Início:** apresentação profissional, tecnologias e links de contato;
- **Sobre mim:** trajetória, forma de trabalho e objetivos profissionais.

## Tecnologias apresentadas

- JavaScript;
- React e React Native;
- Next.js;
- Python e Django;
- Docker;
- AWS;
- Git;
- HTML5 e CSS3.

## Funcionalidades

- Layout responsivo para desktop, tablet e celular;
- navegação entre as páginas Início e Sobre mim;
- links externos para GitHub e LinkedIn;
- seção de tecnologias em destaque;
- chamada para novas oportunidades profissionais;
- HTML semântico e navegação por teclado;
- link para pular diretamente ao conteúdo principal;
- indicação visual da página ativa;
- suporte à preferência de redução de movimentos;
- metadados básicos para mecanismos de busca e compartilhamento.

## Estrutura do projeto

```text
Portifolio/
├── assets/             # Imagens e ícones
├── styles/
│   └── style.css       # Estilos globais, componentes e responsividade
├── about.html          # Página Sobre mim
├── index.html          # Página inicial
└── README.md           # Documentação do projeto
```

## Como executar

### Opção 1 — Abrir diretamente

Clone o repositório e abra o arquivo `index.html` em um navegador.

```bash
git clone <URL-DO-REPOSITORIO>
cd Portifolio
```

Não é necessário instalar dependências.

### Opção 2 — Servidor local

Se tiver Python instalado, execute na raiz do projeto:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000` no navegador. No Windows, se o comando `python` não estiver disponível, tente `py -m http.server 8000`.

## Personalização

### Conteúdo

- Altere a apresentação, tecnologias e links em `index.html`;
- atualize a trajetória profissional em `about.html`;
- substitua os endereços do GitHub e LinkedIn nos dois arquivos quando necessário.

### Cores e tipografia

As principais configurações visuais ficam nas variáveis do início de `styles/style.css`:

```css
:root {
    --fundo: #07111f;
    --texto: #f4f7fb;
    --texto-suave: #9cacc2;
    --destaque: #5eead4;
}
```

Modificar essas variáveis atualiza o tema do site de forma consistente.

## Responsividade

O layout utiliza CSS Grid, Flexbox e unidades fluidas. Os principais pontos de adaptação estão definidos para telas de até `820px` e `520px`.

## Acessibilidade

O projeto inclui:

- regiões semânticas como `header`, `nav`, `main`, `section` e `footer`;
- hierarquia de títulos consistente;
- identificação da página atual com `aria-current`;
- nomes acessíveis para navegação e links sociais;
- estilos de foco visíveis;
- contraste entre texto, fundo e elementos interativos;
- suporte a `prefers-reduced-motion`.

## Publicação

Por ser estático, o portfólio pode ser hospedado em serviços como GitHub Pages, Netlify, Vercel ou AWS. O diretório publicado deve ser a própria raiz do repositório, e o arquivo de entrada é `index.html`.

## Contato

- [GitHub](https://github.com/ViniciusYoda)
- [LinkedIn](https://www.linkedin.com/in/vinicius-yoda-silva/)
