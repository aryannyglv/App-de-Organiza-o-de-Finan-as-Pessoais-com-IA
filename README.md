# 🚀 Assistente de Finanças Pessoais

Este projeto é um protótipo de aplicativo web para organização financeira pessoal, focado em uma experiência de usuário intuitiva e conversacional. O objetivo é permitir o registro e acompanhamento financeiro sem a complexidade de planilhas ou formulários tradicionais, com recursos modernos de personalização.

O aplicativo é construído como um single-page application (SPA) em um único arquivo HTML, utilizando TailwindCSS para estilização e JavaScript puro para toda a lógica de negócios e interatividade.

# ✨ Funcionalidades Principais

O aplicativo é dividido em três seções principais, acessíveis por uma barra de navegação inferior:

1. Chat e Dashboard

Interface Conversacional: Permite ao usuário registrar despesas e receitas usando linguagem natural (ex: "Gastei R$ 50 no mercado").

NLP Simples: Um processador de linguagem natural básico em JavaScript extrai o valor e a categoria da mensagem.

Dashboard Rápido: Exibe o saldo atual, o total de receitas e o total de despesas diretamente na tela principal.

2. Metas Financeiras

Criação de Metas: O usuário pode definir objetivos financeiros (ex: "Reserva de Emergência") com um valor total e um valor já guardado.

Acompanhamento Visual: As metas são exibidas como cartões, cada um com uma barra de progresso visual para fácil acompanhamento.

3. Relatórios e Personalização

Gráfico de Despesas: Um gráfico de pizza (criado com Chart.js) detalha a distribuição de gastos por categoria.

Extrato Detalhado: Uma lista completa de todas as transações (receitas e despesas) registradas.

Personalização:

Modo Claro/Escuro: Um alternador de tema permite ao usuário escolher entre light mode e dark mode.

Temas de Cores: O usuário pode selecionar uma cor de destaque principal para o aplicativo (ex: azul, verde, roxo).

Principles de Design

Design Universal e Acessível: A interface foi projetada para ser limpa, intuitiva e mobile-first. O foco está em fontes legíveis, navegação clara e elementos de fácil interação.

Feedback Imediato: Todas as ações do usuário, como adicionar uma transação ou meta, refletem imediatamente na interface.

# 🛠️ Tecnologias Utilizadas

- HTML5: Estrutura semântica do aplicativo.

- TailwindCSS: Framework CSS utility-first para estilização rápida e responsiva.

- JavaScript (ES6+): Utilizado para toda a lógica do aplicativo, incluindo:

- Manipulação do DOM

- Processamento de linguagem natural (NLP)

- Gerenciamento de estado (abas, modais)

- Persistência de dados

- Chart.js: Biblioteca para a criação do gráfico de pizza na tela de relatórios.

- LocalStorage: Usado para salvar todas as transações, metas e preferências de personalização (tema e cor) no navegador, garantindo que os dados não se percam.


Link: [Aqui está o acesso ao app!](https://lovable.dev/projects/d5554c19-c61a-4af0-8849-91809a2da766?utm_source=lovable-badge)
 

Este README foi gerado com base no PRD e nos requisitos do projeto.
