# Premio-2026# Prêmio TJAC de Qualidade 2026 — Intranet

Seja bem-vindo ao repositório do Prêmio TJAC de Qualidade 2026. Esta é uma aplicação web institucional desenvolvida exclusivamente para a intranet do Tribunal de Justiça do Estado do Acre (TJAC). 

O principal objetivo deste portal é centralizar e facilitar o acesso a todas as informações, critérios e indicadores do prêmio, servindo como um ponto de engajamento e consulta rápida para os nossos servidores.

---

## Tecnologias Utilizadas

* *Core:* React 18 (JSX) + Vite 5 
* *Estilização:* Tailwind CSS 3
* *Ícones:* Lucide React
* *Pós-processamento:* PostCSS & Autoprefixer

---

A estrutura de pastas segue o padrão limpo do Vite, separando os arquivos estáticos do código-fonte principal:


premio-tjac-intranet/
├── public/              # Banner oficial e PDF da Portaria do CNJ
├── src/
│   ├── App.jsx          # Componente raiz (toda a interface da aplicação)
│   ├── main.jsx         # Ponto de entrada do React
│   └── index.css        # Estilos globais e diretivas do Tailwind
├── tailwind.config.js   # Customização de temas do Tailwind
└── vite.config.js       # Configurações de build do Vite


*Conteúdo da Aplicação*
O portal foi desenhado em uma estrutura de página única (Single Page), dividida nos seguintes blocos:

Cabeçalho (Hero): Apresentação oficial com a identidade visual do TJAC, selos do CNJ e o banner do prêmio.

Categorias de Certificação: Detalhamento visual dos níveis de premiação — Excelência (pontuação igual ou superior a 95%), Ouro e Prata — junto aos seus respectivos critérios.

Painel de Indicadores: Cards interativos com links diretos para os dashboards externos (Metas CNJ, ISU e outras métricas estratégicas).

Central da Portaria: Área dedicada à leitura e download da Portaria PRESI TJAC 1961/2026 na íntegra.

Rodapé: Informações institucionais, contatos e links rápidos de suporte.

*Como Rodar o Projeto Localmente*
Pré-requisitos
Antes de começar, certifique-se de ter instalado em sua máquina:

Node.js (versão 18 ou superior)

npm (versão 9 ou superior)

Realização
Tribunal de Justiça do Estado do Acre — TJAC
SUMAE
AC.
