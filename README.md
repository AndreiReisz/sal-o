# Estética Art Stilo — site

Página única em HTML, CSS e JavaScript. Não precisa instalar nada.

## Estrutura

```
index.html          a página inteira
assets/img/         logo e fotos
README.md           este guia
```

## Ver no computador

Dê dois cliques em `index.html`. As imagens só aparecem se a pasta `assets` estiver ao lado dele.

## Publicar no GitHub (link que abre o site)

O GitHub mostra o código quando você abre um arquivo `.html` no repositório. Para o site abrir de verdade, use o GitHub Pages:

1. Crie um repositório novo no GitHub.
2. Envie **o conteúdo desta pasta** (`index.html`, `assets` e `README.md`) para a raiz do repositório. O `index.html` não pode ficar dentro de outra pasta.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
5. Aguarde cerca de 1 a 2 minutos. O link aparece na mesma tela, neste formato: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Trocar o número do WhatsApp

Abra `index.html`, procure por `const CONFIG` perto do final e altere o valor de `whatsapp`. Use só números, com código do país, DDD e telefone. Exemplo: `5551999999999`.

A mensagem que já aparece pronta na conversa está em `message`.

## Trocar as fotos

Substitua os arquivos em `assets/img/` mantendo o mesmo nome. Para os serviços, use fotos horizontais (proporção parecida com 16 por 10). Para a Mary, use uma foto quadrada.
