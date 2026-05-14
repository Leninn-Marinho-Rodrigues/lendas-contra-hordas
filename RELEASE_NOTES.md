# Release Notes

## Versão 1.3

Esta atualização corrige pontos que ficaram faltando na progressão da build e
na preservação de save. O foco foi garantir que, depois do limite, o jogador não
receba habilidades novas por acidente e que builds novas consigam recuperar
progresso salvo por versões anteriores.

### Principais mudanças desde a 1.2

- Limite de habilidades/passivas únicas aumentado de 70 para 75.
- Depois dos 75 espaços, não aparecem cartas novas.
- Após o limite, o level-up só oferece habilidades/passivas que o jogador já tem
  e que ainda podem ser melhoradas.
- Quando tudo que o jogador possui estiver no máximo, novos níveis viram ouro.
- Save agora procura e mescla progresso antigo de caminhos anteriores.
- A migração preserva ouro, classes liberadas, melhorias permanentes e
  estatísticas importantes usando o maior progresso encontrado.

### Comparação rápida

| 1.2 | 1.3 |
| --- | --- |
| Build com 70 espaços únicos | Build com 75 espaços únicos |
| Depois do limite ainda dependia de filtros amplos | Depois do limite só entra o que já está na build |
| Save novo podia esconder progresso antigo | Save antigo é encontrado e mesclado automaticamente |

### Arquivo de download

```text
LendasContraHordas-Windows-v1.3.zip
```

### Como atualizar

Baixe o `.zip`, extraia em uma pasta nova e abra pelo atalho
`Jogar Lendas Contra Hordas.lnk`. O save principal fica em
`Saved Games\LendasContraHordas`; se a versão anterior deixou progresso em outro
caminho conhecido, a build tenta recuperar e mesclar automaticamente.

## Versão 1.2

Esta atualização expande a build jogável e melhora o fechamento das runs. O
foco principal foi deixar o limite de habilidades mais flexível, fortalecer o
Invocador, melhorar invocações supremas, limpar o HUD de eventos, adicionar tela
de vitória e reforçar a validação automática de sprites, VFX, ícones e HUD.

### Principais mudanças desde a 1.1

- Limite de habilidades/passivas únicas aumentado de 60 para 70.
- Depois dos 70 espaços, o jogo ainda oferece upgrades já escolhidos que ainda
  não chegaram ao nível máximo.
- Quando não houver mais upgrade elegível, o level-up passa a virar ouro.
- Lendárias da classe continuam protegidas e lendárias já possuídas têm
  prioridade de evolução.
- Invocador começa com +2 espaços de invocação.
- Dragões lendários ficaram mais fortes, com bolas de fogo maiores, queimadura
  escalável e um quarto dragão de ataque à distância quando o pacto evolui.
- Invocações se curam ao matar inimigos.
- Hydra e Beholder foram reforçados em tamanho, velocidade, dano e IA.
- Mago recebeu pequeno reforço inicial de sobrevivência e poder mágico.
- HUD de eventos ficou compacto, com detalhes sob clique.
- Vitória agora mostra resumo da run: abates, ouro, XP e nível final.
- Menu ganhou trilha de aventura e mistério.
- QA v1.2 ganhou script consolidado para testes, auditorias de sprites, HUD, VFX
  e ícones.

### Comparação rápida

| 1.1 | 1.2 |
| --- | --- |
| Build limitada a 60 espaços únicos | Build com 70 espaços únicos |
| Build cheia passava mais cedo para ouro | Upgrades já escolhidos ainda podem ser maximizados |
| Invocador com início mais lento | Invocador começa com mais invocações e dragões mais fortes |
| Eventos com mais texto direto na HUD | Evento aparece compacto e abre detalhes sob clique |
| Fim da fase voltava rápido ao menu | Tela de vitória mostra o resumo da run |

### Arquivo de download

```text
LendasContraHordas-Windows-v1.2.zip
```

### Como atualizar

Baixe o `.zip`, extraia em uma pasta nova e abra pelo atalho
`Jogar Lendas Contra Hordas.lnk`. O save fica em `Saved Games\LendasContraHordas`
e deve continuar funcionando entre atualizações.

## Versão 1.1

Esta atualização substitui a build pública anterior da vitrine por uma versão
mais clara para jogar e mais organizada para baixar. O foco principal foi
leitura de textos, progressão de build, comportamento do Berserker e apresentação
do projeto no GitHub.

### Principais mudanças desde a vitrine anterior

- Revisão ortográfica de textos visíveis no jogo: menus, cards de classe,
  eventos, vendedor, inventário, level-up, atributos e tela de morte.
- Saída da dungeon maior, mais brilhante e com marcador de direção.
- Berserker do Guerreiro com IA melhor para caçar, priorizar Titans e prender
  inimigos grandes nos cantos do mapa.
- Berserker não desperdiça ativação quando há poucos inimigos no mapa aberto.
- Berserker desativa dentro de dungeon vazia.
- Limite de build ajustado para 60 slots únicos.
- Níveis de uma mesma habilidade contam como 1 slot, não como vários.
- Itens repetidos contam como 1 slot; itens novos ocupam slot.
- O jogo reserva espaço para lendárias da classe dentro do limite.
- Item novo coletado com build cheia vira ouro.
- Vendedor não cobra item único se a build estiver cheia.
- Pasta jogável organizada com atalho, executável, ícone e LEIA-ME.
- Galeria e GIF de gameplay atualizados para representar a build 1.1.

### Comparação rápida

| Antes | Agora na 1.1 |
| --- | --- |
| Textos sem revisão completa | Textos principais revisados com acentos e clareza |
| Saída de dungeon menos evidente | Portal maior, mais brilhante e sinalizado |
| Berserker podia gastar ativação em momento ruim | Berserker avalia melhor o mapa e prioriza alvos relevantes |
| Build podia ficar confusa com repetição de melhorias | 60 slots únicos, com lendárias da classe protegidas |
| Página pública mais simples | README, changelog, prints e GIF explicam melhor a versão |

### Arquivo de download

```text
LendasContraHordas-Windows-v1.1.zip
```

### Como atualizar

Baixe o `.zip`, extraia em uma pasta nova e abra pelo atalho
`Jogar Lendas Contra Hordas.lnk`. O save fica em `Saved Games\LendasContraHordas`
e deve continuar funcionando entre atualizações.

## Public Showcase v0.1.0

This public package presents the current playable direction of **Lendas contra
Hordas** without exposing the private source code.

### Highlights

- Four playable class identities: Warrior, Mage, Archer, and Summoner.
- Horde-survival combat with escalating maps, dungeons, world events, and titan
  encounters.
- Permanent progression layer with class-focused upgrades.
- Pixel-art inspired character, monster, item, projectile, VFX, and UI assets.
- Runtime HUD, merchant, level-up, event, inventory, and map-selection screens.

### Distribution

The Windows playable build is attached to the GitHub Release instead of being
committed directly to the repository. Large binaries do not belong in the Git
history.

Release asset:

```text
LendasContraHordas-Windows-v0.1.0.zip
```
