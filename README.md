# **🏆 Simulador e Calculadora \- Campeonato do Mundo 2026**

Este projeto é uma aplicação web interativa construída num único ficheiro, desenvolvida para simular o Campeonato do Mundo da FIFA de 2026, com a introdução do novo formato de 48 seleções.

## **📌 Descrição**

O Simulador permite aos utilizadores prever e calcular o desenrolar de todo o torneio, desde a fase de grupos até à grande final. A aplicação possui um motor de cálculo em tempo real que atualiza as classificações, determina os apurados (incluindo a complexa regra dos 8 melhores terceiros classificados) e constrói automaticamente a árvore da fase a eliminar (mata-mata).

## **✨ Funcionalidades Principais**

* **⚽ Simulador de Grupos Interativo:** Introduza os resultados de todos os 72 jogos da fase de grupos.  
* **📊 Classificações em Tempo Real:** As tabelas são reordenadas instantaneamente após cada golo inserido. O sistema respeita os critérios de desempate de pontos, diferença de golos e golos marcados.  
* **✅ Destaque Visual de Apuramento:** As 32 equipas qualificadas para a fase seguinte são automaticamente destacadas a verde nas tabelas.  
* **⚔️ Chaveamento Automático do Mata-Mata:** A árvore da fase a eliminar (desde os 16-avos de final) é montada de forma dinâmica consoante as classificações da fase de grupos.  
* **🥅 Suporte a Penáltis:** Se ocorrer um empate num jogo a eliminar, a interface exibe automaticamente botões para o utilizador decidir quem vence através da marcação de penáltis.  
* **👑 Coroação do Campeão:** Quando o resultado da final é preenchido, um banner comemorativo surge no topo da página.  
* **🧹 Limpeza Rápida:** Um botão global de "Limpar Resultados" para reiniciar a simulação rapidamente.

## **🛠️ Tecnologias Utilizadas**

* **HTML5:** Estrutura semântica da aplicação.  
* **CSS / Tailwind CSS:** Estilização moderna e responsiva (via CDN).  
* **JavaScript (Vanilla):** Lógica da aplicação, cálculos de classificação e manipulação do DOM em tempo real.

## **🚀 Como Utilizar**

1. Faça o download ou copie o código do ficheiro copa2026.html.  
2. Dê um duplo clique no ficheiro para o abrir em qualquer navegador web moderno (Chrome, Firefox, Safari, Edge, etc.).  
3. **Aba "Simulador de Grupos":** Insira os resultados desejados nos jogos para ver as tabelas a atualizarem-se.  
4. **Aba "Grupos (Tempo Real)":** Acompanhe o estado de todas as equipas e veja quem se qualifica.  
5. **Aba "Mata-Mata (Tempo Real)":** Avance na simulação introduzindo os resultados dos cruzamentos até descobrir quem levanta o troféu.

## **📱 Responsividade**

A interface foi concebida para funcionar de forma otimizada tanto em ambientes desktop como em dispositivos móveis, com a fase a eliminar implementada numa grelha com deslocamento (scroll) horizontal amigável.
