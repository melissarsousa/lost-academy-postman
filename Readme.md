Projeto de automação com Postman

As collections incluídas são somente aquelas em que todos os testes passaram com sucesso, para simplificar o teste inicial.

## Instalação
''' bash
	npm install -g newman
	npm install -g newman-reporter-htmlextra
'''

## Execução com report html extra
''' bash
	newman run CostCenter.postman_collection.json -e LOST.postman_environment.json 
	newman run CSystem Login.postman_collection.json -e LOST.postman_environment.json 
	newman run UserLogin acess.postman_collection.json -e LOST.postman_environment.json 
'''