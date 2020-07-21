# Newman (instalação execução)

Abaixo segue um resumo da documentação detalhada do [Newman](https://github.com/postmanlabs/newman)

## Pre-requisitos
   1. Ter instalado o nodeJS: https://nodejs.org/en/

Após instalar o nodeJS, executar o seguinte comando para a instalação do Newman: 


```JavaScript
npm install -g newman
```

## Executando os testes

1. Exportar a _collection_ criada no Postman. Ao exportar será gerado o arquivo em formato JSON (*.json):
![](/img-gif/export.png)

1. Executar a _collection_ pelo Newman
```shell
newman run "<nome_da_collection>.json -r htmlextra".
```

![](/img-gif/Exemplo-linha-de-comando.png)

1. Visualizar o resultado da execução, depositado em arquivo HTML pelo comando executado no passo anterior. O resultado será similar à ilustração abaixo:
![](/img-gif/dashboad-html.png)
