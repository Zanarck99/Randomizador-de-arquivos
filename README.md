# Script randomizador de arquivos

Esse script seleciona aleatóriamente um número (aleatório ou definido pelo usuário) de arquivos de dentro de uma pasta escolhida pelo usuário e copia para uma outra pasta.

## Funcionamento:

1. Coloque o executável junto com a pasta com os arquivos que deseja randomizar
2. O prompt irá listar as pastas que estão no mesmo diretório, cada uma com um número correspondente
3. Escolha a pasta onde estão os arquivos pelo número ou selecione uma pasta qualquer do sistema inserindo o caminho da pasta (absoluto ou relativo ao diretório onde está o executável)
4. Selecione uma quantidade de arquivos a serem escolhidos (um único número inteiro, a pasta final vai ter a quantidade de arquivos escolhida) ou um intervalo para que o script escolha o total (mínimo e máximo do intervalo, separado por vígula, dessa forma: <número mínimo> <número máximo>)
    - **OBS:** você pode usar a flag "all" como parâmetro ou limite de intervalo para usar o número total de arquivos da pasta
5. Após isso você pode selecionar uma pasta do sistema como pasta de destino (caso a pasta não exista, o prompt irá solicitar uma confirmação para criar essa pasta) ou aperte "Enter" sem digitar nenhum valor para criar uma pasta chamada _choosed_archives_ no mesmo local do executável para onde os arquivos serão copiados.
6. Por fim, você pode escolher se os arquivos serão renomeados no destino, existem dois métodos de renomeio:
    1. O método padrão, consite de ordenar os arquivos aleatóriamente com números começando por 1 seguido de um underline ("\_") + o nome original do arquivo, dessa forma: \<n>\_\<nome original>
    2. Substiui os nomes originais do arquivo por uma sequência numérica iniciada em 1 (as extensões dos arquivos são mantidas)
    - **OBS:** Caso você escolha renomear os arquivos no destino e aperte "Enter" sem digitar nenhum outro valor na seleção de método, o método [1] será usado.

E pronto, o script irá escolher os arquivos e copiar para a psta selecionada, renomeando caso tenha sido solicitado.

### Observações importantes:

-   O tempo de execução do script varia conforme a quantidade de arquivos processados e o tamanho dos mesmos, então, caso esteja demorando, verifique a barra de progresso no prompt para se certificar que o script não está travado.
-   Tenha em mente que o script ignora subpastas e arquivos dentro de subpastas dentro da pasta escolhida, então, de preferência, coloque todos os arquivos que deseja randomizar em uma única pasta.
