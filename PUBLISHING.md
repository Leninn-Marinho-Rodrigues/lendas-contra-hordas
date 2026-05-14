# Publishing Checklist

Use este checklist para criar o repositório público.

## 1. Criar repositório

Nome sugerido:

```text
lendas-contra-hordas
```

Visibilidade:

```text
Public
```

Descrição:

```text
RPG survivors-like de hordas, classes lendárias, eventos titânicos e progressão permanente para Windows.
```

## 2. Adicionar tópicos

Copie os tópicos de `GITHUB_TOPICS.txt`.

## 3. Subir somente este pacote

Suba o conteúdo da pasta `public_showcase/`, não a raiz completa do projeto.

## 4. Criar release

Crie uma tag com a versão pública atual. A sequência combinada é:

```text
v1.1
v1.2
v1.3
```

A versão só deve avançar quando o desenvolvedor pedir uma publicação nova no
GitHub. Anexe o build Windows como asset da release, por exemplo:

```text
LendasContraHordas-Windows-v1.2.zip
```

Não commit arquivos `.exe` ou `.zip` no repositório.

## 4.1 Atualizar changelog

Antes de publicar, atualize:

- `README.md`, com o link da versão atual.
- `RELEASE_NOTES.md`, com o resumo da release.
- `CHANGELOG.md`, com o que mudou em relação à versão anterior.

## 5. Configurar preview social

Em **Settings > Social preview**, use:

```text
media/hero.png
```
