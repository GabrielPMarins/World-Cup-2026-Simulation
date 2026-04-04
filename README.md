# **🏆 Simulador Oficial \- Copa do Mundo FIFA 2026**

Um simulador web interativo, responsivo e em tempo real para a **Copa do Mundo da FIFA de 2026**, construído em um único arquivo HTML. Este projeto implementa rigorosamente o novo formato da competição com **48 seleções**, 12 grupos e a inédita fase de 16-avos de final (Round of 32).

## **✨ Funcionalidades Principais**

* **📊 Classificação em Tempo Real:** Conforme os placares são digitados, a tabela de cada grupo é atualizada instantaneamente aplicando os critérios de desempate oficiais da FIFA (1. Pontos, 2\. Saldo de Gols, 3\. Gols Pró).  
* **🎯 Regra dos Terceiros Colocados:** O algoritmo identifica automaticamente as 2 primeiras seleções de cada grupo e calcula de forma dinâmica os **8 melhores 3º colocados** para avançarem ao mata-mata.  
* **⚔️ Chaveamento Dinâmico (Mata-Mata):** A árvore eliminatória inicia com marcações (placeholders) que indicam a origem de cada vaga (ex: "1º Grupo A", "3º C/D/F/G/H"). Assim que um grupo recebe resultados, as seleções assumem suas posições na chave automaticamente.  
* **🥅 Decisão por Pênaltis:** Detecção inteligente de empates nos jogos eliminatórios, gerando botões na interface para o usuário decidir qual seleção avança após a prorrogação/pênaltis.  
* **📱 Mobile-First:** Interface altamente otimizada para smartphones. Utiliza teclados numéricos nativos para digitação rápida de placares (inputmode="numeric"), rolagem horizontal suave (swipe) e layout ajustado para não quebrar em telas menores.  
* **📲 Compartilhamento no WhatsApp:** Ao definir o campeão, o sistema utiliza a biblioteca html2canvas para gerar uma imagem PNG estilizada de um "Pódio" com o Campeão e o Vice, permitindo o compartilhamento direto pelo WhatsApp ou Web Share API nativa.  
* **🧹 Botão de Reinício Rápido:** Limpa todos os resultados e zera a simulação com um único clique.

## **🛠️ Tecnologias Utilizadas**

Este projeto foi desenvolvido focado em simplicidade, performance e portabilidade (Single-File Application):

* **HTML5 & CSS3**  
* **JavaScript Vanilla (ES6+)**: Toda a lógica de estado, algoritmos de chaveamento e reatividade do DOM, sem necessidade de frameworks pesados.  
* **Tailwind CSS (via CDN)**: Estilização utilitária rápida e design responsivo.  
* **html2canvas**: Renderização de elementos do DOM para geração da imagem de compartilhamento do campeão.

## **⚙️ Regras Implementadas (Manual FIFA 2026\)**

O simulador foi desenhado respeitando as seguintes normativas projetadas para o formato de 2026:

1. **Fase de Grupos:** 12 grupos (A a L) com 4 times cada. Avançam 32 seleções no total.  
2. **Distribuição do Round of 32:** Segue o manual oficial de cruzamentos inaugurais (Jogos 1 a 16), onde os vencedores de grupos enfrentam os segundos colocados ou uma combinação matemática específica dos melhores terceiros colocados.

## **🚀 Como Executar o Projeto**

Como a aplicação é construída em um formato de arquivo único, não é necessário rodar processos de build complexos, configurar servidores locais ou ter o Node.js instalado.

1. Faça o clone deste repositório:  
   git clone \[https://github.com/seu-usuario/simulador-copa-2026.git\](https://github.com/seu-usuario/simulador-copa-2026.git)

2. Navegue até o diretório do projeto.  
3. Abra o arquivo copa2026.html diretamente em qualquer navegador moderno (Google Chrome, Safari, Firefox, Edge).  
4. *Dica de Hospedagem:* Você pode hospedar gratuitamente através do **GitHub Pages** ou **Vercel** subindo apenas este arquivo HTML.

## **🤝 Como Contribuir**

Contribuições, relatórios de bugs (issues) e pull requests são muito bem-vindos\! Se você encontrar alguma falha na lógica de classificação ou tiver uma ideia de melhoria na Interface de Usuário:

1. Faça um *Fork* do projeto.  
2. Crie uma *Branch* para sua alteração (git checkout \-b feature/MelhoriaIncrivel).  
3. Faça o *Commit* das suas mudanças (git commit \-m 'feat: Adiciona MelhoriaIncrivel').  
4. Faça o *Push* para a Branch (git push origin feature/MelhoriaIncrivel).  
5. Abra um *Pull Request*.

## **📜 Licença**

Distribuído sob a licença MIT.

*Desenvolvido para os amantes do futebol mundial e entusiastas de simulações esportivas.*