Dicente: Helena Bretas Goulart  
Matrícula: 16/0124034  
Turma: 35T45  

## Containerização
Versão utilizada no Docker: 19.03.12
Versão utilizada no Docker-compose: 1.29.1

#### Proposta de solução
O backend, frontend e o banco de dados se encontram em conteineres. Para conferir como se deu essa organização, basta [clicar aqui](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/docker-compose.yml).
O comando `docker-compoose up --build` irá auxiliar nesta etapa.

## Integração e Deploy contínuos
As ferramentas utilizadas nesta etapa foram: CodeClimate e Digital Ocean

### Proposta de solução
Para conferir os scripts que informam o comportamento do projeto na integração contínua, basta acessar [este documento](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/.github/workflows/ci.yml). Já sobre o script do deploy contínuo pode ser [visto aqui](https://github.com/helenagoulart/Trabalho-Individual-2020-2/blob/master/.github/workflows/deploy.yml).

#### É possível verificar que ambos funcionam (deploy e integração) na imagem abaixo:

![actions](https://i.imgur.com/4sHhNBa.png)

Para verificar como estão fucionando o deploy e a integração, basta ir em **Actions** e ver os workflows disponíveis. É importante ressaltar que a cada PR aberto, o deploy e a integração são realizados. 

#### Tratando-se das métricas colhidas através do CodeClimate, obtive:

![codeclimate](https://i.imgur.com/ryHXCpK.jpg)


## Para conferir o projeto funcionando, basta acessar http://165.227.206.253:8081
