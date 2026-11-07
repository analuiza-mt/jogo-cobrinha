# 🐍 Neon Snake

Um jogo da cobrinha inspirado nos clássicos arcades, desenvolvido com HTML5, CSS3 e JavaScript puro. O projeto apresenta uma interface moderna com estética neon, diferentes níveis de dificuldade e suporte para dispositivos móveis.

O objetivo é controlar a cobra, coletar alimentos, aumentar sua pontuação e superar seu próprio recorde sem colidir com as paredes ou com o próprio corpo.

## 🎮 Demonstração

O jogo pode ser executado diretamente no navegador, sem necessidade de instalação ou conexão com a internet.

## ✨ Funcionalidades

- **Três níveis de dificuldade:** Fácil, Médio e Difícil.
- **Pontuação:** Ganhe 10 pontos a cada alimento coletado.
- **Recorde pessoal:** A melhor pontuação é armazenada no navegador.
- **Velocidade progressiva:** A cobra fica mais rápida conforme a pontuação aumenta.
- **Sistema de pausa:** Pause e retome a partida a qualquer momento.
- **Reinício de partida:** Comece uma nova rodada sem recarregar a página.
- **Detecção de colisões:** O jogo termina ao atingir as paredes ou o próprio corpo.
- **Controles para dispositivos móveis:** Botões direcionais para jogar em celulares e tablets.
- **Interface responsiva:** Layout adaptável a diferentes tamanhos de tela.
- **Feedback visual:** Animações, efeitos neon e notificações de novo recorde.
- **Funcionamento offline:** Jogue sem depender de servidores ou conexão com a internet.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura da página e elementos do jogo. |
| CSS3 | Estilização, layout responsivo, animações e efeitos visuais. |
| JavaScript (Vanilla) | Lógica do jogo, movimentação, colisões, pontuação e controles. |
| HTML5 Canvas | Renderização do tabuleiro, cobra e alimentos. |
| LocalStorage | Armazenamento persistente do recorde no navegador. |

### Recursos utilizados

- CSS Grid e Flexbox para organização do layout.
- Media Queries para responsividade.
- CSS Variables para personalização das cores.
- Canvas API para desenho e renderização.
- DOM API para manipulação dos elementos da interface.
- `setInterval()` para controlar o ciclo de movimentação.
- `localStorage` para persistência dos recordes.

## 🕹️ Como jogar

O objetivo é coletar os alimentos espalhados pelo tabuleiro e fazer a cobra crescer, acumulando pontos.

Atenção: não encoste nas paredes nem no próprio corpo da cobra!

### Controles

| Ação | Teclado | Dispositivos móveis |
|---|---|---|
| Mover para cima | `W` ou `↑` | Botão ↑ |
| Mover para baixo | `S` ou `↓` | Botão ↓ |
| Mover para esquerda | `A` ou `←` | Botão ← |
| Mover para direita | `D` ou `→` | Botão → |
| Pausar / Continuar | `Espaço` | Botão Pausar |
| Iniciar partida | `Enter` | Botão Iniciar |

## 🎯 Níveis de dificuldade

O jogo possui três níveis, cada um com uma velocidade inicial e progressão próprias.

| Dificuldade | Descrição |
|---|---|
| Fácil | Ideal para iniciantes, com movimentação mais lenta. |
| Médio | Velocidade equilibrada para jogadores intermediários. |
| Difícil | Movimentação rápida, exigindo reflexos e precisão. |

A dificuldade pode ser selecionada antes de iniciar uma partida. Durante o jogo, a velocidade aumenta progressivamente conforme os pontos são acumulados.

## 🚀 Como executar o projeto

Não é necessário instalar dependências, frameworks ou ferramentas adicionais.

1. Faça o download ou clone este repositório.
2. Localize o arquivo `index.html`.
3. Abra o arquivo diretamente em um navegador.
4. Clique em **Iniciar jogo** e divirta-se!

## 📁 Estrutura do projeto

O jogo foi desenvolvido em um único arquivo HTML, contendo a estrutura, os estilos e a lógica de funcionamento.

```text
Neon-Snake/
│
└── index.html
```

- **HTML:** estrutura da interface.
- **CSS:** estilos e responsividade.
- **JavaScript:** lógica e funcionalidades do jogo.

## 🎨 Design e interface

O projeto utiliza uma identidade visual inspirada em jogos arcade e estética cyberpunk.

Principais características:

- Tema escuro com tons de verde neon.
- Elementos visuais em amarelo e vermelho.
- Efeitos de brilho e sombras.
- Painéis com informações da partida.
- Interface adaptável para diferentes dispositivos.

## 📚 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de praticar e aprimorar conhecimentos em desenvolvimento Front-End, lógica de programação e manipulação de elementos gráficos utilizando tecnologias nativas da web.

Também busca explorar conceitos como:

- Manipulação do DOM.
- Estruturas de dados e arrays.
- Lógica de movimentação e colisão.
- Gerenciamento de estados do jogo.
- Eventos de teclado e interação por toque.
- Armazenamento de dados no navegador.
- Responsividade e experiência do usuário.

## 🔮 Possíveis melhorias futuras

- Adicionar efeitos sonoros.
- Implementar novos modos de jogo.
- Criar um ranking de pontuações.
- Adicionar temas visuais alternativos.
- Implementar novos desafios e objetivos.

## 👩‍💻 Desenvolvido por

**Ana Luiza Magalhães Teixeira**

Estudante de Ciência da Computação e desenvolvedora em constante aprendizado, explorando novas tecnologias e criando projetos para aprimorar habilidades em programação.
Feito no curso **IA Generativas Aplicada a Programação - Chat GPT**

---

⭐ Se você gostou do projeto, deixe uma estrela no repositório!
