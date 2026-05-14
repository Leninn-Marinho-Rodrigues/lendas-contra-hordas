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

**Versão pública atual: 1.1**

Esta versão melhora a leitura e o ritmo da run, com saída de dungeon mais fácil
de localizar, Berserker mais inteligente, limite de build em 60 slots únicos e
mais proteção para as lendárias da classe.

### O que mudou na 1.1

- **Textos revisados:** menus, eventos, vendedor, inventário, level-up e tela de
  morte passaram por revisão de ortografia e acentuação.
- **Berserker mais inteligente:** o Guerreiro caça melhor, evita ativar em
  momentos vazios e pressiona criaturas grandes com mais decisão.
- **Dungeons mais legíveis:** a saída ficou maior, mais brilhante e mais fácil
  de encontrar quando a tela está cheia de monstros.
- **Build mais controlada:** o limite agora é de 60 slots únicos; melhorar uma
  habilidade já escolhida não ocupa novos slots.
- **Lendárias protegidas:** o limite de build reserva espaço para as lendárias
  da própria classe.
- **Pasta de jogador limpa:** a build vem com executável, atalho, ícone e
  `LEIA-ME.txt`, sem arquivos de desenvolvimento.

## Preview

![Gameplay preview](media/gameplay-preview.gif)

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
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/releases/download/v1.1/LendasContraHordas-Windows-v1.1.zip
```

### Como baixar e jogar

1. Clique no link de download acima.
2. Aguarde o arquivo `.zip` baixar. Ele tem cerca de 412 MB.
3. Clique com o botão direito no arquivo baixado e escolha **Extrair tudo**.
4. Abra a pasta extraída.
5. Dê dois cliques em `Jogar Lendas Contra Hordas.lnk`.
6. Se o atalho não abrir no seu Windows, execute `LendasContraHordas.exe`.

Se o Windows mostrar aviso do SmartScreen, clique em **Mais informações** e
depois em **Executar mesmo assim**. Isso pode acontecer porque a build de teste
ainda não possui assinatura digital.

### Como atualizar sem perder progresso

1. Baixe o `.zip` da versão nova.
2. Extraia em uma pasta nova, por exemplo `LendasContraHordas-v1.1`.
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
https://github.com/Leninn-Marinho-Rodrigues/lendas-contra-hordas/releases/tag/v1.1
```

Nessa página, abra a área **Assets** e baixe:

```text
LendasContraHordas-Windows-v1.1.zip
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
