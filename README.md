# Processamento-Paralelo-Ass-ncrono
Desafio Kotlin Processamento Paralelo/Assíncrono

Descrição
No mundo da programação, frequentemente enfrentamos situações onde múltiplas tarefas precisam ser executadas simultaneamente para otimizar o tempo de resposta ou processamento. Um exemplo comum é o download de múltiplos arquivos da internet.

Para este desafio, suponha que você tenha uma lista de URLs que deseja "baixar". Seu objetivo é simular o download desses arquivos de forma paralela e imprimir o tamanho de cada URL após seu "download" ter sido disparado. Para simplificar, cada URL leva exatamente 1 segundo para ser "baixado".

Requisitos:

Defina uma lista de URLs que você deseja "baixar".
Crie uma função para simular o "download" de uma URL. Essa função deve aceitar uma URL como entrada e retornar o tamanho da URL.
Implemente uma lógica que permita iniciar o "download" de várias URLs em paralelo.
Imprima o tamanho de cada URL na ordem em que foram inseridas.
Entrada
A entrada consiste em uma lista de URLs, uma em cada linha. Uma linha vazia indica o fim da lista.

Saída
A saída deve mostrar o tamanho de cada URL na ordem em que foram inseridas, seguido pelo "Tempo total", que é simplesmente a contagem de URLs (por mais conta-intuitivo que pareça 😁):
Iniciando downloads...
Arq1: $tamanhoUrl1
Arq2: $tamanhoUrl2
Tempo total: $quantidadeDeUrls

Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada	Saída
https://chat.openai.com/
https://www.invertexto.com/
https://web.dio.me/
[Linha vazia]
Iniciando downloads...
Arq1: 24
Arq2: 27
Arq3: 19
Tempo total: 3
https://www.netflix.com/
https://www.hbomax.com/
https://www.amazon.com.br/
[Linha vazia]
Iniciando downloads...
Arq1: 24
Arq2: 23
Arq3: 26
Tempo total: 3
https://refactoring.guru/
https://github.com/
https://stackoverflow.com/
[Linha vazia]
Iniciando downloads...
Arq1: 25
Arq2: 19
Arq3: 26
Tempo total: 3
Nota: A simulação de download é uma forma simplificada de entender como tarefas paralelas podem ser disparadas e como os resultados podem ser coletados de volta na ordem desejada.

