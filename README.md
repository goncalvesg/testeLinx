# testeLinx

# O Md5sum do resultado foi o seguinte: c9e9abda344c4ac4f7c3edb2de8b62f3

# O código utilizado para fazer a ordenação se encontra neste repositório, para executá-lo basta digitar: python sorting.py huge.log hugeOut.log -k"(linhe[0:4])" onde os arquivos .log são a entrada e saída, respecticamente, o parâmetro -k indica a posição da linha que servirá como parâmetro para a ordenação, como as linhas eram de caracteres aleatórios, escolhi as 5 primeiras posições da linha, mas em um arquivo de log real é possível escolher as posições redefentes à datas e horários quando ocorreram os logs existem ainda outros dois parametros que podem ser adicioandos após o 'key' que são a linha buffer sinalizado por -b, seguido pelo tamanho do buffer e por padrão é utilizado 32000 linhas e o último parâmetro é o -t, que sinaliza um diretório temporário para utilizar durante a ordenação, em relação
# à este diretório, se for em outro disco rígido diferente de onde o arquivo se encontra, o código oferece uma performance melhor.

# Enfim, acredito que seja isso.

# Abraços.
