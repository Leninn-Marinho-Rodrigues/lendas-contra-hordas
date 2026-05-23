# Lendas contra Hordas

![Lendas contra Hordas hero](media/hero.png)

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-dc3545)
![Platform](https://img.shields.io/badge/platform-Windows-2f81f7)
![Genre](https://img.shields.io/badge/genre-survivors--like-f6c177)
![License](https://img.shields.io/badge/license-proprietary-lightgrey)

**Lendas contra Hordas** é um RPG survivors-like para Windows, com combate
contra hordas, classes com identidade própria, eventos mundiais, dungeons,
progressão permanente e criaturas titânicas.

Este repositório é uma **vitrine pública** do jogo. Ele mostra o projeto,
prints, GIFs, notas e informações de download, mas o código-fonte completo e os
documentos internos de design continuam privados.

## Versão Atual

**Versão pública atual: 1.5.2**

Esta versão amplia a identidade de controle de mapa do **Alquimista**. A Mesa
Alquímica agora tem novas misturas para contaminar, desacelerar e prender hordas
sem aumentar o excesso de projéteis na tela.

### O que mudou na 1.5.2

- **Miasma Andarilho:** bolsões de gás tóxico surgem em aglomerações,
  envenenam a horda e semeiam Praga Alquímica.
- **Esporos Contagiosos:** o contágio salta entre monstros, acelera a propagação
  da praga e empilha stacks com facilidade.
- **Lodo Epidêmico:** cria áreas vivas que prendem, desaceleram, corroem defesas
  e deixam focos de contágio pelo mapa.
- **Controle sem spam visual:** as novas misturas usam áreas persistentes,
  contágio e efeitos de campo, evitando voltar ao excesso de projéteis.
- **Build Windows atualizada:** pacote de download recriado como
  `LendasContraHordas-Windows-v1.5.2.zip`, mantendo o save fora da pasta do jogo.

### O que mudou na 1.5.1

- **Homúncula mais controlada:** limite de velocidade para impedir movimentos
  bruscos ou saltos visuais pelo mapa.
- **Coleta por vórtice:** ingredientes alquímicos passam a ser atraídos para a
  Homúncula e para o Alquimista, reduzindo deslocamentos exagerados.
- **Forma final como guardiã:** no estágio 20, a Homúncula permanece próxima do
  Alquimista, orbitando, lançando maldições, conjurando proteções e auxiliando a
  luta sem abandonar o mestre.
- **Mídia pública nova:** GIF e prints mostram a Mesa Alquímica, a progressão da
  Homúncula e o vórtice de ingredientes funcionando.
- **Build Windows atualizada:** pacote de download recriado mantendo o save fora
  da pasta do jogo, para preservar progresso entre atualizações.

### Base adicionada na 1.5

- **Nova classe jogável: Alquimista:** frascos, bombas, mutações, poções e
  alquimia mágica em uma classe flexível de dano, defesa, recursos e suporte.
- **Mesa Alquímica:** ingredientes coletados durante a partida abrem um menu
  próprio de receitas que não ocupa os espaços normais da composição.
- **Homúncula evolutiva:** a parceira do Alquimista coleta apenas ingredientes,
  ataca, protege o mestre, acumula biomassa, revive sem perder progresso e
  escala por receitas.
- **Árvore de receitas da Homúncula:** Tecido Reforçado, Núcleo Faminto,
  Membrana Guardiã, Mãos Alquímicas, Síntese Dupla, Instinto Protetor, Ritual de
  Renascimento e Mimetismo Mutagênico.
- **Sprites novos validados:** Alquimista ganhou estágios visuais de evolução e
  a Homúncula recebeu 20 estágios, do gel instável inicial até a forma final
  arcana.
- **Cards de heróis reescritos:** o menu de personagens agora explica melhor o
  estilo, pontos fortes, riscos e mecânicas centrais de cada classe.
- **Save preservado:** a versão continua usando o sistema de save fora da pasta do
  jogo, com busca e mescla de progresso antigo para não apagar conquistas.

## Preview

![Alquimista e Homúncula](media/alchemist-homuncula-v1-5-1.gif)

![Controle alquímico 1.5.2](media/alchemy-control-v1-5-2.gif)

![Gameplay preview](media/gameplay-preview.gif)

![Beholder protegendo o Mago](media/beholder-ai-v1-4-5-guard.gif)

![Plano de dungeon lendária](media/beholder-ai-v1-4-5-dungeon.gif)

![Estresse de fim de run](media/beholder-ai-v1-4-5-endgame.gif)

## Galeria

| Menu | Seleção de mapa |
| --- | --- |
| ![Menu](media/screenshots/menu.png) | ![Seleção de mapa](media/screenshots/map-select.png) |

| Guerreiro | Mago |
| --- | --- |
| ![Guerreiro em combate](media/screenshots/warrior-field.png) | ![Mago em dungeon](media/screenshots/mage-dungeon.png) |

| Arqueiro | Invocador |
| --- | --- |
| ![Arqueiro em combate](media/screenshots/archer-field.png) | ![Invocador em evento titânico](media/screenshots/summoner-titan-event.png) |

| Level-up | Vendedor |
| --- | --- |
| ![Tela de level-up](media/screenshots/level-up.png) | ![Vendedor](media/screenshots/merchant.png) |

| Invocações lendárias |
| --- |
| ![Progressão de invocações lendárias](media/screenshots/legendary-summons-progress.png) |

| Novidades 1.5 |
| --- |
| ![Card do Alquimista no menu](media/screenshots/alchemist-class-detail-v1-5.png) |
| ![Evolução visual do Alquimista](media/screenshots/alchemist-tier-progression-v1-5.png) |
| ![20 estágios da Homúncula](media/screenshots/homuncula-tier-progression-v1-5.png) |
| ![Conceito da Mesa Alquímica](media/screenshots/alchemy-table-concept-v1-5.png) |

| Ajustes 1.5.2 |
| --- |
| ![Controle alquímico de mapa](media/screenshots/alchemy-control-v1-5-2.png) |

| Ajustes 1.5.1 |
| --- |
| ![Homúncula atraindo ingredientes](media/screenshots/alchemist-homuncula-vortex-v1-5-1.png) |
| ![Mesa Alquímica em jogo](media/screenshots/alchemy-table-runtime-v1-5-1.png) |
| ![Card da Homúncula no HUD](media/screenshots/homuncula-status-card-v1-5-1.png) |

| Novidades 1.4.5 |
| --- |
| ![Evidência da IA do Beholder](media/screenshots/beholder-ai-v1-4-5-summary.png) |
| ![Aprendizado persistente do Beholder](media/screenshots/beholder-ai-v1-4-5-learning.png) |
| ![Plano defensivo em dungeon lendária](media/screenshots/beholder-ai-v1-4-5-dungeon-plan.png) |

| Novidades 1.4.1 |
| --- |
| ![Árvore de farm 1.4.1](media/screenshots/legendary-summons-v1-4-1-top.png) |
| ![Marcos longos 1.4.1](media/screenshots/legendary-summons-v1-4-1-tree.png) |
| ![Colheita lendária em dungeon](media/screenshots/legendary-dungeon-harvest-v1-4-1.png) |

## O que o jogo tem

- Combate em tempo real contra hordas.
- Classes com habilidades e passivas próprias.
- Dungeons e eventos mundiais com riscos e recompensas.
- Monstros comuns, épicos, lendários e titânicos.
- Itens, melhorias permanentes, vendedor e progressão entre runs.
- HUDs, efeitos, sprites e áudio pensados para leitura rápida em combate.

## Download

### Download rápido

Baixe a build pública mais recente aqui:

```text
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/releases/download/v1.5.2/LendasContraHordas-Windows-v1.5.2.zip
```

### Como baixar e jogar

1. Clique no link de download acima.
2. Aguarde o arquivo `.zip` baixar. Ele tem cerca de 520 MB.
3. Clique com o botão direito no arquivo baixado e escolha **Extrair tudo**.
4. Abra a pasta extraída.
5. Dê dois cliques em `Jogar Lendas Contra Hordas.lnk`.
6. Se o atalho não abrir no seu Windows, execute `LendasContraHordas.exe`.

Se o Windows mostrar aviso do SmartScreen, clique em **Mais informações** e
depois em **Executar mesmo assim**. Isso pode acontecer porque a build de teste
ainda não possui assinatura digital.

### Como atualizar sem perder progresso

1. Baixe o `.zip` da versão nova.
2. Extraia em uma pasta nova, por exemplo `LendasContraHordas-v1.5.2`.
3. Abra pelo atalho `Jogar Lendas Contra Hordas.lnk`.
4. O save local fica fora da pasta do jogo, em `Saved Games\LendasContraHordas`.
5. Por isso, atualizar a pasta do jogo não deve apagar seu progresso.

### O que vem na pasta do jogador

A pasta baixada foi organizada para ser simples:

```text
LendasContraHordas.exe
Jogar Lendas Contra Hordas.lnk
LEIA-ME.txt
app_icon.ico
```

Não é necessário instalar Python, abrir terminal ou baixar arquivos paralelos.

### Baixar pela página de Releases

Também dá para baixar pela página da release:

```text
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/releases/tag/v1.5.2
```

Nessa página, abra a área **Assets** e baixe:

```text
LendasContraHordas-Windows-v1.5.2.zip
```

## Controles

| Ação | Teclas |
| --- | --- |
| Movimento | WASD ou setas |
| Escolher melhoria | 1, 2, 3 ou clique |
| Pausar / menu | Esc |
| Inventário | I |
| Interagir | E |

## Feedback dos jogadores

Se você testar o jogo, seu feedback ajuda muito.

### Como enviar feedback pelo GitHub

1. Entre na página de feedback:

```text
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/issues
```

2. Clique no botão verde **New issue**.
3. Escolha um modelo:

- **Playtest feedback**: conte como foi sua experiência jogando.
- **Bug report**: relate travamentos, erros, textos cortados ou sprites estranhos.
- **Sugestão**: mande ideias de habilidades, monstros, balanceamento ou melhorias.

4. Preencha os campos do modelo.
5. Se puder, anexe print ou vídeo curto arrastando o arquivo para a caixa de texto.
6. Clique em **Submit new issue**.

### O que escrever no feedback

O feedback mais útil costuma responder:

- qual classe você jogou;
- quanto tempo sobreviveu;
- se o jogo ficou fácil, difícil ou confuso;
- se algum texto ficou cortado;
- se algum sprite, som ou efeito pareceu estranho;
- prints ou vídeos curtos, se puder mandar.

Exemplo simples:

```text
Joguei de Mago por 9 minutos no mapa inicial.
Gostei das magias e dos efeitos, mas achei a dungeon comum difícil cedo demais.
O texto do evento ficou um pouco grande na tela.
Não travou no meu PC.
```

Guia completo:

```text
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/blob/main/docs/como-dar-feedback.md
```

## Apoie o projeto

Lendas contra Hordas está sendo feito por uma pessoa só, no tempo livre. Se
você gostou do projeto e quiser ajudar a manter as atualizações, pode apoiar via
Pix:

```text
leninn.works@gmail.com
```

Qualquer apoio ajuda com tempo de desenvolvimento, testes, arte, áudio,
ferramentas e futuras builds.

## Status

Projeto em desenvolvimento ativo. As imagens mostram uma build funcional, mas
nomes, balanceamento, efeitos, interface, sons e progressão podem mudar.

## Proteção do projeto

Este repositório não é open source. A vitrine foi montada para mostrar o jogo
sem entregar a implementação completa. Veja [NOTICE.md](NOTICE.md) e
[LICENSE.md](LICENSE.md).

## Links

- [Release notes](RELEASE_NOTES.md)
- [Press kit](docs/press-kit.md)
- [Publicação e proteção](docs/protecao-e-publicacao.md)
- [Roadmap público](docs/roadmap.md)
