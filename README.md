Meu Início de Dia (Personal Dashboard)

Um dashboard de produtividade pessoal dinâmico, focado em organização diária e bem-estar visual. Construído com foco em **UI/UX Premium**, o projeto utiliza paletas de tons pastéis terrosos, tipografia moderna e efeitos avançados de *Glassmorphism* para criar uma experiência de usuário extremamente agradável.

Funcionalidades

- **Dashboard de Estatísticas Dinâmico:** Cards de atenção no topo que calculam automaticamente e em tempo real a sua carga de trabalho (Eventos de Hoje, Eventos da Semana e Tarefas Pendentes).
- **Lista de Tarefas (To-Do List):** Um sistema rápido para adicionar, concluir e remover tarefas diárias.
- **Calendário Interativo de Estudos:** Um calendário gerado dinamicamente via JavaScript onde é possível clicar em qualquer dia e registrar blocos de estudo, provas ou lembretes.
- **Mensagem do Dia:** O painel apresenta uma frase inspiradora rotativa automática com base no dia do ano, oferecendo ânimo logo pela manhã.
- **100% Offline e Privado:** Todos os dados (tarefas e eventos do calendário) são salvos utilizando a API de `localStorage` do navegador. Os dados nunca saem do dispositivo do usuário, garantindo privacidade absoluta e carregamento instantâneo.

Design e UI/UX

O design foi projetado para se afastar da estética fria de painéis corporativos, focando no conforto:
- **Efeito Aurora:** O plano de fundo conta com *blobs* (manchas de cor) animados e espalhados com `filter: blur`, que flutuam suavemente pela tela em cores como terracota, sálvia e mostarda.
- **Glassmorphism 2.0:** Os containers e cards imitam placas de vidro fosco, utilizando `backdrop-filter`, bordas translúcidas e sombras suaves.
- **Tipografia Editorial:** Combinação harmônica das fontes *Plus Jakarta Sans* (para leitura clara e moderna) e *Dancing Script* (para títulos cursivos impactantes).
- **Micro-interações:** Respostas táteis através de CSS puro, com elementos que levantam, flutuam e ganham foco (`pop-out`) ao passar o mouse.
- **Responsividade Total:** Desenvolvido com CSS Grid e Flexbox, adaptando-se perfeitamente de grandes monitores até telas de smartphones.

Tecnologias Utilizadas

O projeto foi construído inteiramente utilizando as tecnologias fundamentais da web, sem o uso de frameworks complexos, garantindo máxima performance e entendimento do código:

- **HTML5:** Estruturação semântica.
- **CSS3:** Animações (`@keyframes`), Variáveis de escopo global (`:root`), Grid/Flexbox e Filtros visuais.
- **JavaScript Vanilla:** Manipulação direta da DOM (DOM Scripting), cálculos de data/hora (`Date` object), escuta de eventos (`Event Listeners`) e persistência de dados (`Window.localStorage`).

Como usar na sua máquina

Como o projeto é estático e não requer servidor backend ou banco de dados, usá-lo é extremamente simples:

1. Faça o clone deste repositório:
   ```bash
   git clone https://https://github.com/Kath-Fernandes/dashdiario

Feito com 🤎 para otimizar os estudos e o trabalho.

Projeto feito no curso Programaria Sprint IA no trabalho com ajuda especial do Google Antigravity
