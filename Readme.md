Projeto de automação com Postman

As collections incluídas são somente aquelas em que todos os testes passaram com sucesso, para simplificar o teste inicial. No entanto, a collection CostCenter não está incluída na pipeline, por estar com um problema por conta dos scripts pre-request, problema este que está sendo resolvido no momento.

## Instalação
``` bash
	npm install -g newman
	npm install -g newman-reporter-htmlextra
```

## Execução com report html extra
``` bash
	newman run CostCenter.postman_collection.json -e LOST.postman_environment.json 
	newman run CSystem Login.postman_collection.json -e LOST.postman_environment.json 
	newman run UserLogin acess.postman_collection.json -e LOST.postman_environment.json 
```
