# Script randomizador de arquivos
Esse script seleciona um número aleatório de arquivos de dentro de uma pasta escolhida pelo usuário e copia para uma outra pasta

## Funcionamento:
1. Coloque o executável junto com a pasta com os arquivos que deseja randomizar
2. O prompt irá listar as pastas que estão no mesmo diretório, cada uma com um número correspondente
3. Escolha a pasta onde estão os arquivos pelo número ou selecione uma pasta quaquer do sistema inserindo o caminho da pasta (absoluto ou relativo ao diretório onde está o executável)
4. Selecione uma quantidade de arquivos a serem escolhidos (um único número inteiro, a pasta final vai ter a quantidade de arquivos escolhida) ou um intervalo para que o script escolha o total (mínimo e máximo do intervalo, separado por vígula, dessa forma: <número mínimo> <número máximo>)

E pronto, o script irá escolher os arquivos e copiar para uma pasta chamada *choosed_archives* criada na mesma pasta onde está o executável do script