# Desafio Back-end

Por favor, leia atentamente as instruções abaixo antes de iniciar o desafio. Em caso de dúvidas, entre em contato que estaremos à disposição.

## Instruções

1. Crie um repositório no GitHub para armazenar todo o código que utilizar para solucionar o problema. 
2. Copie o link do repositório que criar e envie no e-mail `iure.brandao@voxelgestao.com` com o assunto `Desafio Backend - Seu Nome` até o dia (0X/05) às 10:00, horário de Brasília. Não podendo editar, adicionar e nem excluir qualquer arquivo após esse horário. 
3. Não aceitaremos códigos plagiados.
4. Leia atentamente e siga todos os passos da aba [Requisitos](#requisitos).
5. O candidato que não cumprir os requisitos acima, estará automaticamente eliminado.

## Problema

A sigla API deriva da expressão inglesa *Application Programming Interface* que, traduzida para o português, pode ser compreendida como uma interface de programação de aplicação. Por meio de APIs, desenvolvedores podem criar novos softwares e aplicativos capazes de se comunicar com outras plataformas, a fim de capturar informações relevantes. 

Nesse contexto, o seu objetivo é desenvolver um programa em Python, que busque e manipule os dados da API pública: [https://dummyjson.com/products](https://dummyjson.com/products). 

Essa API retorna em `json` uma lista de produtos à venda, em que cada produto contém campos como: categoria (`category`), preço (`price`) e o título (`title`) desse produto. O objetivo do seu programa é imprimir no terminal a média dos preços de todos os produtos da categoria `smartphones`, da seguinte forma:
```
## Resultado da coleta de dados ##
Preço média dos smartphones: $ <valor_medio>.
```
Substituindo `<valor_medio>` pelo valor médio cálculo pelo seu programa. 
Exemplificando, se o programa desenvolvido calculou uma média de 500, ele deverá imprimir no terminal dessa forma:
```
## Resultado da coleta de dados ##
Preço média dos smartphones: $ 500.
```



### **Extra**: 
Caso queira incrementar a solução do seu problema, guarde todos os produtos em uma tabela de banco de dados com os seguintes campos:
- Id
- Title
- Category
- Price

Ao final, imprima uma piada aleatória sobre o nosso querido Chuck Norris para descontrair um pouco a pessoa que está executando o seu programa. Para isso, utilize a API pública: [https://api.chucknorris.io/](https://api.chucknorris.io/)


## Requisitos

- O código deverá ser exclusivamente feito na linguagem Python.
- O repositório deverá conter uma documentação simples de como rodar o projeto.
- O código deverá imprimir as informações coletadas no terminal com a formatação exemplificada na aba [Problema](#problema)
- Bibliotecas terceiras são bem-vindas para a solução do problema.
- *Dica*: Utilize a biblioteca [Requests](https://pypi.org/project/requests/)  para te auxiliar no desenvolvimento da solução.
- *Dica*: Utilize a biblioteca  SQLAlchemy](https://pypi.org/project/SQLAlchemy/) para te auxiliar no desenvolvimento *extra* da solução.
