# node-cli
Exemplo de uma CLI em Node para procurar arquivos em uma pasta.

## Instalação
Para instalar localmente e poder usar o comando no terminal, use o comando:

`npm link`

O comando `search-files` vai estar disponível no terminal. Você pode usar o comando passando o nome do arquivo que deseja procurar no diretório atual:

`search-files .json`

Neste exemplo, listaria todos os arquivos com a extensão `.json`.

## Editando o comando
Você pode editar livremente o arquivo `bin/search-files-cli` para mudar o comportamento do comando sem precisar rodar o comando `npm link` novamente. Qualquer alteração feita nesse arquivo já irá refletir no comando `search-files`.

## Bônus - Ganhe até R$100 pra testar a hospedagem da Umbler!
Está procurando uma hospedagem bacana pra testar e até mesmo publicar tuas aplicações, sites e afins em alguns segundos? É só acessar [este link](http://bit.ly/CreditosNaUmbler) e ganhe até R$100 pra testar o serviço. 

## Observações
Este código faz parte do curso **_Desenvolvendo ferramentas de linha de comando em Node.js_** na [Digital Inovation One](https://digitalinnovation.one).
