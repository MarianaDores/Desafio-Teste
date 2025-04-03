Desafio 

Api JSONPlaceholder - https://jsonplaceholder.typicode.com

Mapeamento de cenário de teste

Cenário 1: Validação do status.

Resultado esperado: Status code is 200.

Dado que é passado todos os dados corretos na requisição
Quando clico em Send
Então a requisição me retorna Status code is 200


Cenário 2: Validação da estrutura do Json.

Resultado esperado: validando estrutura do body.

Dado a estrutura do endpoint 
Quando clico em Send
Então a requisição retorna validando estrutura do body


Cenário 3: Validação do tempo de resposta.

Resultado esperado: Response time is less than 200.

Dado que o limite de tempo que estabeleci para resposta foi 500 e o tempo fixado 200
Quando clico em Send
Então retorna retorna Response time is less than 200


Relatório

file:///D:/Backup/Documentos/Teste/report.html
