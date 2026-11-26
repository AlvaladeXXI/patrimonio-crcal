# Patrimônio CRCAL — protótipo

## Arquivos
- `index.html`: consulta pública por `?id=NUMERO`.
- `gerador.html`: cadastro temporário, QR Codes, importação/exportação de JSON e impressão A4.
- `bens.json`: base pública de demonstração.

## Publicação
Envie os arquivos para a raiz do repositório `patrimonio-crcal`, mantendo GitHub Pages em `main` e `/(root)`.

Abra o gerador em:
https://alvaladexxi.github.io/patrimonio-crcal/gerador.html

## Atualizar a base
1. Importe o `bens.json` atual no gerador.
2. Adicione os novos bens.
3. Clique em “Baixar bens.json”.
4. Substitua o arquivo `bens.json` no GitHub pelo arquivo baixado e faça Commit changes.
5. Aguarde a atualização do GitHub Pages.

## Atenção
Este protótipo é estático: o gerador não grava diretamente no GitHub. A atualização da base exige publicar o novo `bens.json`.
O arquivo `bens.json` é público. Não inclua dados pessoais ou informações internas/sensíveis. O QR Code usa o endereço `https://alvaladexxi.github.io/patrimonio-crcal/?id=NUMERO`.
