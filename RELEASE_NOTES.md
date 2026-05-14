# Release Notes

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
