# Horizon Smart Tutors - Frontend (MVP) 🎨

Este é o repositório de frontend da plataforma de tutores inteligentes da **Oásis Tech & Horizon**.

O projeto foi desenhado sob a premissa de máxima performance, leveza e facilidade de integração através do mecanismo exclusivo de incorporação via **iframe** (embed).

## 🛠️ Tecnologias Utilizadas

- **HTML5 & Vanilla JavaScript:** Optou-se por não utilizar frameworks pesados (como React ou Next.js) para garantir compatibilidade imediata com qualquer navegador e eliminar etapas lentas de build ou dependências do NPM.
- **Tailwind CSS (via CDN):** Utilizado para construir uma interface moderna, responsiva, escura e polida, alinhada à identidade visual de produtos premium.

## 📱 Estrutura das Páginas

- **`admin.html` (Painel de Gestão):** Área administrativa onde o cliente pode criar, listar e gerenciar tutores, além de copiar diretamente o snippet do `<iframe>` pronto para colar em seu próprio site.
- **`widget.html` (Widget do Chat):** Página dedicada a rodar de forma isolada dentro do iframe. Ela gerencia sessões de conversação locais através do `localStorage` e se comunica com o backend via requisições HTTP assíncronas.

## ⚙️ Diretrizes de Integração (Iframe Only)

Não há dependência de jogos complexos de SSO ou LTI. A comunicação e isolamento de sessão são controlados via parâmetros na URL e armazenamento local no navegador do usuário final.

*Este projeto foi desenvolvido de forma 100% assistida por agentes de IA (Gemini & Cursor) para modelagem de telas e scripts de integração assíncronos.*

## 🚀 Como Rodar o Projeto Localmente

Por se tratar de uma aplicação de arquivos estáticos, não há necessidade de etapas de instalação.

1. Clone o repositório.
2. Abra o arquivo `admin.html` diretamente em qualquer navegador de sua preferência.
