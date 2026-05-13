# Publicação e Proteção

Este repositório foi preparado como uma vitrine pública, não como um repositório
de desenvolvimento aberto.

## Publicar sem entregar o jogo inteiro

Incluído:

- README com descrição clara.
- Screenshots e GIF leve.
- Press kit público.
- Release notes.
- Licença proprietária.
- Tópicos sugeridos para descoberta.

Não incluído:

- código-fonte;
- scripts internos;
- documentos completos de design;
- prompts e assets brutos;
- builds commitadas diretamente;
- saves locais, logs, testes e workbench.

## Builds

Publique builds jogáveis na aba **Releases**, não no Git. Isso evita binários
grandes no histórico e deixa a página inicial focada na apresentação.

## Versionamento público

A vitrine pública usa versões simples: `1.1`, `1.2`, `1.3` e assim por diante.
Só avance a versão quando uma nova build for publicada no GitHub a pedido do
desenvolvedor.

Cada versão pública deve ter:

- changelog com o que mudou;
- release notes curtas;
- asset `.zip` na aba Releases;
- README apontando para o download mais recente.

O repositório público continua sem código-fonte completo. A build jogável é
distribuída como pacote Windows fechado, enquanto a implementação, ferramentas
internas, testes, prompts e documentos privados ficam fora da vitrine.

## Tópicos sugeridos

Veja `GITHUB_TOPICS.txt`.

## Descrição sugerida para o GitHub

```text
RPG survivors-like de hordas, classes lendárias, eventos titânicos e progressão permanente para Windows.
```

## Social preview

Use `media/hero.png` como imagem de preview social do repositório.
