# Changelog

As versões públicas seguem uma numeração simples:

- `1.1`, `1.2`, `1.3`... para atualizações públicas pedidas pelo desenvolvedor.
- Correções pequenas podem usar patch, como `1.3.1`, quando servem para corrigir
  uma versão recém-publicada sem virar uma atualização grande.
- A numeração só avança quando uma nova versão é publicada no GitHub.
- Builds internas de teste podem existir, mas não entram neste changelog público.

## Versão 1.5.2 - 2026-05-23

### Controle alquímico de mapa

- Adicionada a receita **Miasma Andarilho**, que cria bolsões de gás tóxico em
  aglomerações, envenena monstros e semeia Praga Alquímica.
- Adicionada a receita **Esporos Contagiosos**, que faz o contágio saltar entre
  monstros próximos, acelera a propagação e empilha stacks de praga.
- Adicionada a receita **Lodo Epidêmico**, que prende, desacelera, corrói defesas
  e cria focos de contágio em áreas de horda.
- As novas misturas conversam com a Praga Alquímica existente e aumentam o
  potencial de controle de mapa do Alquimista sem criar spam de projéteis.
- Poções básicas de veneno e ácido também passam a se beneficiar desses novos
  caminhos de alquimia.

### Build, mídia e validação

- Versão do jogo atualizada para `1.5.2`.
- Adicionado GIF/print público mostrando as três novas linhas de controle
  alquímico.
- Build Windows recriada para download como
  `LendasContraHordas-Windows-v1.5.2.zip`.
- Validação local executada com suíte completa e smoke test do executável.
- Save continua fora da pasta do jogo e não foi alterado pela atualização.

## Versão 1.5.1 - 2026-05-22

### Homúncula e Alquimista

- Homúncula recebeu limite de velocidade para parar de saltar visualmente de um
  ponto a outro do mapa.
- Ingredientes alquímicos agora são atraídos por vórtice para a Homúncula e para
  o Alquimista.
- A forma final da Homúncula não corre mais atrás dos itens pelo mapa; ela fica
  próxima do Alquimista, orbitando em velocidade constante.
- No estágio 20, a Homúncula prioriza papel de bruxa guardiã: conjura maldições,
  proteções, magias de controle e suporte sem abandonar o mestre.
- O comportamento novo mantém a coleta de ingredientes e a Mesa Alquímica sem
  alterar o save nem apagar progresso.

### Mídia, build e publicação

- Adicionado GIF público do Alquimista com a Homúncula final em campo.
- Adicionados prints da Mesa Alquímica em jogo, do vórtice de ingredientes e do
  card da Homúncula no HUD.
- Versão do jogo atualizada para `1.5.1`.
- Build Windows recriada para download como
  `LendasContraHordas-Windows-v1.5.1.zip`.

## Versão 1.5 - 2026-05-22

### Nova classe Alquimista

- Adicionada a classe Alquimista, focada em frascos, bombas, mutações, poções,
  ciência mágica e biologia instável.
- O Alquimista usa a progressão normal por nível, com habilidades e passivas da
  própria classe, mas também possui uma trilha separada por ingredientes.
- Ingredientes alquímicos caem durante a partida e podem abrir a Mesa Alquímica,
  onde o jogador escolhe receitas de poções, mutações e melhorias.
- A progressão por ingredientes não ocupa o limite normal da composição, criando uma
  identidade própria para o Alquimista sem quebrar a regra de slots.

### Homúncula e receitas

- Homúncula principal agora acompanha o Alquimista em combate, coleta apenas
  ingredientes, ataca inimigos, acumula biomassa e protege o mestre.
- A Homúncula revive depois de morrer sem perder o progresso já conquistado.
- Adicionada uma árvore de receitas dedicada para a Homúncula: Tecido Reforçado,
  Núcleo Faminto, Membrana Guardiã, Mãos Alquímicas, Síntese Dupla, Instinto
  Protetor, Ritual de Renascimento e Mimetismo Mutagênico.
- As receitas aumentam vida, regeneração, dano, velocidade, coleta, rendimento de
  ingredientes, escudos, controle de campo e comportamento protetor.
- O visual da Homúncula possui 20 estágios, começando como gel instável e
  avançando aos poucos até uma forma arcana final.

### Interface e apresentação

- Cards de detalhes dos heróis foram reescritos para explicar melhor como cada
  classe joga, suas passivas, lendárias, riscos e pontos fortes.
- O card do Alquimista agora descreve Mesa Alquímica, ingredientes, Homúncula,
  receitas e a diferença entre melhorias por nível e progressão por alquimia.
- A vitrine pública recebeu imagens da evolução visual do Alquimista e da
  Homúncula.
- Save continua fora da pasta do jogo e a atualização mantém compatibilidade com
  progresso antigo.

## Versão 1.4.5 - 2026-05-20

### IA adaptativa do Beholder

- Beholder Titânico recebeu uma camada de decisão mais inteligente para proteger
  o Mago em dungeons, eventos, fim de run, cercos e situações de vida baixa.
- A IA agora registra aprendizado por contexto e por canal de resposta.
- Contextos monitorados: evento, dungeon épica, dungeon lendária, fim de run,
  vida baixa do Mago, vida baixa do Beholder, multidão, projétil, zona hostil e
  Titan.
- Canais de resposta: guarda, esquiva, caça, controle e rota.
- Campo Antimagia, Oráculo de Contingência, Olho Onisciente e Plano da Dungeon
  Lendária foram priorizados para impedir mortes rápidas do Mago.
- Beholder passou a reagir melhor a projéteis, dano em área, contato corpo a
  corpo e gargalos de dungeon.
- Respawn do Beholder foi corrigido para voltar em tempo curto após morte,
  preservando farm e atributos acumulados.
- O HUD de invocações lendárias mostra melhor a leitura de IA, conexões e
  progresso de aprendizado.

### Validação da 1.4.5

- 500 simulações em dungeon épica: 500 sobrevivências, 0 mortes do Beholder.
- 500 simulações em dungeon lendária: 500 sobrevivências, 0 mortes do Beholder.
- 500 simulações de fim de run/eventos: 500 sobrevivências, 0 mortes do Beholder.
- Total validado: 1.500 cenários automatizados, com fontes de perigo separadas
  em contato, área e projétil.
- Test suite completa executada antes da build: 250 testes passaram.
- Build Windows recriada com smoke test aprovado.

### Mídia e publicação

- Adicionados três GIFs públicos da IA do Beholder: guarda do Mago, plano de
  dungeon lendária e estresse de fim de run.
- Adicionados cards visuais com evidência de teste, aprendizado persistente e
  plano defensivo.
- Link de download e documentação pública atualizados para `v1.4.5`.
- Save continua fora da pasta do jogo e segue compatível com atualizações.

## Versão 1.4.1 - 2026-05-19

### Árvore longa das invocações supremas

- Hydra Titânica e Beholder Titânico agora têm 25 marcos de farm, mantendo os
  marcos antigos e adicionando uma camada de farm extremo para saves avançados.
- Hydra recebeu marcos novos como Pele Regenerativa, Colheita de Dungeon,
  Mordida de Elite, Muralha de Cabeças, Sangue Soberano, Devoradora Lendária,
  Guarda Abissal e Rainha do Fim da Run.
- Beholder recebeu Campo Antimagia, Olho Cartógrafo, Geometria Impossível,
  Protocolo de Contingência, Oráculo de Elites, Labirinto Mental, Núcleo
  Regenerativo e Mente Onisciente.
- A trilha longa agora continua além de 5.000 de farm: Hydra chega a 30.000
  banquetes e Beholder chega a 56.000 focos arcanos.
- A Hydra ganhou Caçada Primordial, Coração de Leviatã, Ninho de Relíquias,
  Mandíbula de Cerco, Sangue Imortal, Três Tronos, Guardiã do Abismo,
  Devora-Mundos e Hydra Eterna.
- O Beholder ganhou Grande Beholder, Olho do Labirinto, Análise Predatória,
  Cúpula Antimagia, Arquitetura Impossível, Tesoureiro Arcano, Mente de Cerco,
  Oráculo Imortal e Olho Onisciente.
- Os novos marcos têm efeitos reais: cura, escudo, debuffs, controle de campo,
  zonas na saída da dungeon, coleta de recursos, cristais, baús e itens em
  abates raros.
- O HUD de invocações lendárias foi ajustado para exibir 25 marcos, símbolos
  visuais de categoria, grupos de habilidade e progresso sem perder a leitura.
- Novos efeitos sonoros dedicados foram adicionados para mordida, rugido profundo
  e passos da Hydra, além de raio, feixe central e cúpula antimagia do Beholder.
- Foram adicionados novos prints e GIF público da progressão lendária 1.4.1.

### Save e teste local

- A atualização preserva as mesmas chaves de save da Hydra e do Beholder, então
  os stacks antigos continuam válidos.
- O save local do desenvolvedor foi preparado para teste com as quatro melhorias
  permanentes lendárias liberadas.

## Versão 1.4 - 2026-05-19

### Invocações lendárias e HUD de progressão

- Criada uma aba mais rica para invocações lendárias no inventário, com barra de
  progresso por farm, nós animados, categorias de habilidade e marcos futuros.
- Hydra Titânica e Beholder Titânico agora exibem claramente o que já foi
  liberado, o próximo marco e como cada criatura evolui em dano, defesa,
  controle de campo e oportunidades de dungeon/evento.
- A árvore de farm das invocações supremas foi expandida para 8 estágios, com
  descrições curtas para facilitar a leitura durante a run.
- Beholder recebeu sprite sheet nova gerada no Gemini, tratada para fundo
  transparente e validada na pipeline strict do jogo.
- Beholder ganhou regeneração, guarda do mago, matriz de oportunidade e
  comportamento tático mais forte para atacar, reposicionar e proteger.
- Hydra ganhou mais leitura de progressão e reforço de identidade como chefe
  aliada permanente que devora, protege e domina áreas.
- Abates feitos por áreas e projéteis das invocações supremas agora continuam
  alimentando o farm permanente correto.
- Respawn de Hydra e Beholder preserva os acúmulos salvos, sem apagar o poder
  conquistado em runs longas.

### Qualidade e save

- Save continua fora da pasta baixada e a versão mantém compatibilidade com
  saves anteriores, preservando ouro, classes, melhorias e estatísticas.
- Auditorias de sprites, animações e textos de HUD foram executadas para evitar
  sprites transparentes/cortados e textos fora das caixas.

## Versão 1.3.1 - 2026-05-14

### Correção da build fechada

- Corrigido o caso em que a HUD mostrava uma build acima de 75/75 slots, mas o
  level-up ainda oferecia habilidades novas.
- O limite agora usa os slots reais da build, incluindo habilidades/passivas e
  itens equipados.
- Depois de 75/75, o jogo só oferece melhorias que o jogador já possui e que
  ainda não estão no nível máximo.
- Lendárias novas não são injetadas quando a build já está cheia; lendárias já
  possuídas continuam podendo subir de nível.
- Quando tudo que já está na build estiver maximizado, o level-up vira ouro.

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
