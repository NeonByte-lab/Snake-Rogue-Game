# 🐍 Snake Rogue — Dungeon Edition

> Um clássico arcade reinventado como um roguelite! Explore masmorras, enfrente criaturas, colete relíquias, evolua sua serpente e derrote os Guardiões.

## 🎮 Sobre o projeto

**Snake Rogue** é uma releitura do clássico jogo da cobrinha (Snake), combinando mecânicas tradicionais de arcade com elementos de RPG e roguelite.

O jogador controla uma serpente em uma masmorra dividida em diferentes salas. Durante a aventura, precisa coletar alimentos, derrotar inimigos, acumular experiência e adquirir melhorias para sobreviver aos desafios cada vez maiores.

A cada três salas, um poderoso Guardião aparece para testar as habilidades do jogador.

O projeto foi desenvolvido inteiramente com tecnologias nativas da Web, sem frameworks ou dependências externas.

## ✨ Funcionalidades

### 🐍 Sistema de movimentação
- Movimentação contínua da serpente.
- Controles por teclado (setas e WASD).
- Controles por toque e gestos em dispositivos móveis.
- Crescimento ao consumir alimentos.
- Detecção de colisões.
- Velocidade progressiva.

### ⚔️ Sistema de combate
- Inimigos que perseguem o jogador.
- Sistema de pontos de vida.
- Escudos para absorver danos.
- Habilidade especial de pulso energético.
- Chefes com barra de vida e padrões de ataque.

### 🗺️ Exploração de masmorras

O jogo possui diferentes tipos de salas:

| Sala | Descrição |
|---|---|
| ⚔️ Combate | Enfrente inimigos para liberar a saída. |
| 💎 Tesouro | Colete cristais e ganhe pontos extras. |
| 🌿 Descanso | Recupere vida e receba um escudo. |
| 👹 Boss | Enfrente um Guardião poderoso. |

Os Guardiões aparecem a cada três salas.

### 📈 Sistema de progressão

O jogador acumula experiência (XP) ao coletar alimentos e cristais.

Ao subir de nível, recebe a oportunidade de escolher uma relíquia que modifica suas habilidades.

### 💎 Relíquias disponíveis

| Relíquia | Efeito |
|---|---|
| ⚡ Escamas velozes | Aumenta a velocidade de movimentação. |
| 🛡️ Escudo arcano | Adiciona proteção contra danos. |
| 🧲 Ímã de éter | Aumenta o alcance de coleta de cristais. |
| 💚 Coração antigo | Recupera pontos de vida. |
| 💥 Núcleo explosivo | Adiciona uma carga de pulso. |
| 🐍 Corpo ancestral | Aumenta o tamanho da serpente e concede pontos. |

## 🎯 Como jogar

O objetivo é sobreviver pelo maior número possível de salas, derrotando inimigos e chefes enquanto fortalece sua serpente.

**Controles:**

| Tecla | Ação |
|---|---|
| ↑ ↓ ← → | Movimentar |
| W A S D | Movimentar |
| Espaço | Pausar / Continuar |
| X | Disparar pulso energético |
| 1, 2, 3 | Selecionar relíquias |

Em dispositivos móveis, utilize os botões direcionais ou deslize o dedo sobre a área de jogo.

## 🏆 Pontuação e recordes

O sistema de pontuação recompensa diferentes ações:

- 🍎 Consumir alimentos: +10 pontos.
- 💎 Coletar cristais: +3 pontos.
- 👹 Derrotar um Guardião: +100 pontos.
- 💰 Entrar em uma sala de tesouro: +15 pontos.

O recorde é armazenado utilizando `localStorage`, permitindo manter a melhor pontuação entre diferentes partidas e visitas ao navegador.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura da interface e área de jogo. |
| CSS3 | Estilização, layout responsivo, efeitos e animações. |
| JavaScript (Vanilla) | Lógica do jogo, movimentação, combate e progressão. |
| Canvas API | Renderização gráfica da serpente, inimigos, alimentos e cenários. |
| LocalStorage | Persistência do recorde do jogador. |

### Arquitetura

O projeto utiliza uma estrutura simples, concentrada em um único arquivo HTML.

- **HTML:** organiza os elementos da interface.
- **CSS:** controla a identidade visual e a responsividade.
- **JavaScript:** implementa a classe principal `SnakeRogue`, responsável pelo gerenciamento do jogo.

## 🚀 Como executar

Não é necessário instalar dependências, configurar servidores ou utilizar ferramentas adicionais.

1. Baixe o arquivo `index.html`.
2. Localize o arquivo no computador.
3. Abra-o com dois cliques.
4. Escolha começar a aventura.
5. Sobreviva às masmorras!

**Requisitos:** navegador moderno com suporte a HTML5, Canvas e JavaScript.

## 📱 Responsividade

A interface foi projetada para funcionar em diferentes dispositivos:

- 💻 Computadores.
- 📱 Smartphones.
- 📲 Tablets.

Os controles se adaptam a dispositivos com tela sensível ao toque.

## 🎨 Identidade visual

O jogo utiliza uma estética inspirada em jogos arcade e RPGs de fantasia:

- Interface escura com elementos neon.
- Destaques em verde, azul, roxo e vermelho.
- Painel de atributos e progressão.
- Indicadores de vida, experiência e pontuação.
- Barra de vida dos chefes.
- Diário de eventos da aventura.

## 📂 Estrutura do projeto

```text
Snake-Rogue/
│
├── snake-rogue-dungeon.html
│
└── README.md
```

Todo o código-fonte do jogo está concentrado no arquivo HTML.

## 🎓 Objetivos de aprendizado

Este projeto também permite praticar conceitos importantes de desenvolvimento Front-end:

- Manipulação do DOM.
- Programação orientada a objetos.
- Manipulação de eventos.
- Estruturas condicionais e de repetição.
- Gerenciamento de estados.
- Renderização com Canvas API.
- Temporizadores e animações.
- Armazenamento local.
- Design responsivo.
- Organização e modularização de código.

## 🔮 Possíveis melhorias futuras

- 🗺️ Sistema de mapas com salas conectadas.
- 👾 Novos tipos de inimigos.
- 👑 Diferentes chefes com habilidades próprias.
- 🧪 Sistema de inventário e equipamentos.
- 🧬 Novas evoluções para a serpente.
- 🎵 Efeitos sonoros e trilha sonora.
- 🏅 Conquistas e desafios.
- 💾 Sistema de salvamento de progresso.

---

**Snake Rogue — Dungeon Edition**

*Entre na masmorra. Evolua sua serpente. Derrote os Guardiões. Sobreviva!* 🐍⚔️

Desenvolvido com HTML5, CSS3 e JavaScript puro.
