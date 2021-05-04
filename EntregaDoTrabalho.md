Dicente: Helena Bretas Goulart  
Matrícula: 16/0124034  
Turma: 35T45  


## Containerização
Versão utilizada no Docker: 19.03.12

#### Proposta de solução
O backend, frontend e o banco de dados se encontram em conteineres. Para conferir como se deu essa organização, basta [clicar aqui](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/docker-compose.yml).
O comando `docker-compoose up --build` irá auxiliar nesta etapa.


## Integração contínua
As ferramentas utilizadas nesta etapa foram: CodeClimate e Travis.

### Proposta de solução
Para conferir os scripts que informam o comportamento do projeto na integração contínua, basta acessar [este documento](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/.travis.yml).
Tratando-se das métricas colhidas através do CodeClimate, obtive:

## Deploy contínuo
A ferramenta utilizada foi o Node JS Package, indicado pelo próprio Github para este projeto.

### Proposta de solução
O script do deploy contínuo é [encontrado aqui](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/.github/workflows/npm-publish.yml).
