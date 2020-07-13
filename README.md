# Newman Instalaçãoo e Execução da automação.

## Pre-requisitos
   1. Ter instalado o nodeJS: https://nodejs.org/en/

Após instalar o nodeJS, executar o seguinte comando para a instalação do Newman: 


```JavaScript
npm install -g newman
```

## Executando os testes

1. Exportar a Collection: Para utilizar o Newman é necessário ter a collections da suite criada no Postman, ou seja, a estrutura com as requisições para testes. Ao exportar será gerado o arquivo em formato JSON (*.json):
![](/img-gif/export.png)

2. Executando o Newman: Abrir a pasta onde foi salva a collection em formato JSON via terminal.

3. Linha de comando: Na tela do 'cmd' informar o comando newman run "<nome_da_collection>.json -r htmlextra".
![](/img-gif/Exemplo-linha-de-comando.png)

Isso iniciará execução dos testes e poderá ser visualizado em run time:

Dentro da Pasta onde foi executado a linha de comando, será criado a seguinte página html:
![](/img-gif/dashboad-html.png)
