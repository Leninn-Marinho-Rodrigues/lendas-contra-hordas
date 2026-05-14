# Changelog

As versões públicas seguem uma numeração simples:

- `1.1`, `1.2`, `1.3`... para atualizações públicas pedidas pelo desenvolvedor.
- A numeração só avança quando uma nova versão é publicada no GitHub.
- Builds internas de teste podem existir, mas não entram neste changelog público.

## Versão 1.3 - 2026-05-14

### Progressão e build

- Limite de habilidades/passivas únicas aumentado de 70 para 75.
- Ao alcançar 75 espaços únicos, o jogo deixa de oferecer habilidades, passivas
  ou cartas novas.
- Depois do limite, o level-up passa a mostrar apenas melhorias que o jogador já
  possui e que ainda podem subir de nível.
- Quando todas as melhorias elegíveis estiverem no nível máximo, o level-up vira
  ouro automaticamente.
- A regra também impede que cartas novas entrem por acidente depois do limite,
  mantendo a build fechada e mais previsível.

### Save e atualização

- Sistema de save agora procura locais usados por versões anteriores e mescla o
  progresso encontrado.
- A migração preserva ouro, classes liberadas, melhorias permanentes e
  estatísticas importantes usando sempre o maior progresso encontrado.
- Isso evita que uma build nova comece com save vazio quando já existia progresso
  em `user_data` ou em outro caminho antigo.
- O save principal continua em `Saved Games\LendasContraHordas`, fora da pasta
  do jogo, para facilitar atualizações sem apagar progresso.

## Versão 1.2 - 2026-05-13

### Progressão e upgrades

- Limite de habilidades/passivas únicas aumentado de 60 para 70.
- Melhorar uma habilidade já escolhida continua contando como apenas 1 espaço da
  build, independentemente do nível dela.
- Depois de ocupar os 70 espaços, o level-up ainda oferece habilidades e
  passivas já escolhidas que ainda não chegaram ao nível máximo.
- Quando todas as opções elegíveis estiverem no máximo, o level-up passa a virar
  ouro automaticamente.
- Lendárias da classe continuam protegidas dentro do limite.
- Se o jogador já possui uma lendária da classe que ainda pode melhorar, ela tem
  prioridade sobre novas lendárias.

### Classes e invocações

- Invocador começa naturalmente com +2 espaços de invocação.
- Invocações recuperam 3% da vida máxima ao matar inimigos.
- Dragões lendários do Invocador ficaram mais fortes, com bolas de fogo maiores,
  queimadura escalável e acúmulos de poder.
- Ao fortalecer os três dragões principais, surge um quarto dragão focado em
  ataques à distância.
- Hydra suprema recebeu mais tamanho, velocidade, dano, crescimento por devorar
  inimigos e novas ações ofensivas.
- Beholder recebeu mais velocidade, dano e IA de alvo melhorada para usar lasers
  em grupos perigosos.
- Mago começa com um pouco mais de vida, defesa e poder mágico inicial.

### Interface, áudio e fechamento de run

- HUD de eventos ficou mais limpo: a tela mostra apenas um aviso curto, e o card
  detalhado abre quando o jogador clica.
- Ao concluir uma fase, o jogo mostra uma tela de vitória com abates, ouro, XP e
  nível final antes de voltar ao menu.
- Menu ganhou música própria com clima de aventura e mistério.
- Processo de QA v1.2 documentado e automatizado em `scripts/run_v1_2_quality_gate.ps1`.

### Qualidade técnica

- Auditorias de sprites, VFX, ícones, HUD e fluidez dos personagens foram
  reforçadas.
- O pacote do jogador continua preservando o save local em
  `Saved Games\LendasContraHordas`, para que atualizações não apaguem progresso.

## Versão 1.1 - 2026-05-13

### Melhorias de gameplay

- Berserker do Guerreiro ficou mais inteligente ao caçar inimigos.
- Berserker agora prioriza criaturas grandes, resistentes, lendárias e Titans.
- Contra Titans e criaturas enormes, o Guerreiro tenta prender o alvo nos cantos
  do mapa para continuar atacando sem deixar o inimigo escapar do alcance.
- Berserker não ativa no mapa aberto quando há menos de 10 criaturas vivas.
- Berserker se acalma dentro de dungeon quando não há mais criaturas para caçar.
- Recarga da passiva Berserker foi levemente aumentada.

### Dungeons

- Saída da dungeon ficou maior e mais fácil de localizar.
- Portal de saída ganhou brilho, feixe vertical e marcador de tela.
- Área de interação da saída foi aumentada para funcionar melhor em momentos de
  caos.

### Progressão e build

- Limite da build agora é de 60 slots únicos.
- Melhorar uma habilidade para nível 2, 3 ou mais continua contando como apenas
  1 slot.
- Itens repetidos também contam como apenas 1 slot.
- Itens novos contam como slot de build.
- O jogo reserva espaço para as lendárias da própria classe dentro do limite.
- Se a build estiver cheia, item novo coletado no chão vira ouro.
- O vendedor não cobra item único quando a build está cheia.

### Interface e leitura

- HUD da build agora mostra `Build: X/60 slots`.
- Revisão ortográfica dos textos principais do jogo, incluindo menus, eventos,
  cards de classe, inventário, vendedor e tela de morte.
- `LEIA-ME.txt` do pacote jogável foi revisado com instruções mais claras de
  abertura, controles e atualização sem perder save.
- Textos e instruções públicas de download foram simplificados.
- Pasta de jogador organizada para abrir pelo atalho.

### Vitrine pública

- Prints da galeria e GIF de gameplay atualizados com a build 1.1 revisada.
- README reorganizado para explicar melhor as melhorias desta versão.
- Release notes ampliadas para comparar a versão 1.1 com a vitrine anterior.

## Public Showcase v0.1.0 - 2026-05-12

- Primeira vitrine pública do projeto.
- Galeria com prints e GIF.
- Release pública inicial para Windows.
- Documentação de feedback, apoio via Pix e proteção do projeto.
