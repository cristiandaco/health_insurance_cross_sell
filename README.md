# Health Insurance Cross Sell

## Contexto do problema

O nosso cliente é uma seguradora que forneceu Seguro Saúde para seus clientes, agora eles precisam de ajuda na construção de um modelo para prever se os segurados (clientes) do ano passado também terão interesse no Seguro Automóvel oferecido pela empresa.

![How-health-insurance-](https://user-images.githubusercontent.com/81040797/146363458-13cb65b7-c42a-42dc-bd86-24b4eec1aae4.jpg)

## Estrutura da Solução

1. Descrição dos dados
2. Feature engeneering
3. Análise exploratória
4. Preparação dos dados
5. Feature selection
6. Machine Leearning modeling
7. Model performance
8. Publicação do modelo em produção

## Premissas Assumidas
1. A intenção de adquirir o seguro automóvel é diretamente influenciada pelo fato do cliente já possuir seguro saúde.
2. A venda cruzada aumenta a fidelidade dos clientes.
3. Um modelo de Machine Learning que consiga fazer o Rankeamento dos clientes mais propensos a adiquirir o seguro automóvel pode reduzir os custos de venda.

## Insights
### Clientes do sexo feminino deveriam ter mais interesse em adquirir o seguro do que cliente do sexo masculino
**Falso**. Apenas **10,4%** dos cliente do genero feminino tem interesse em adquirir o seguro, já **13,84%** dos cliente do genero masculino possuem interesse
![image](https://user-images.githubusercontent.com/81040797/146605510-2755ca8b-e5df-4df8-b041-a74067fc2c6b.png)

### Clientes mais velhos devem ter mais interesse em adquirir o seguro do que clientes mais jovens
**Verdadeiro.** Clientes acima 35 anos representam **73,18%** dos clientes que possuem interesse em adquirir o seguro.
![image](https://user-images.githubusercontent.com/81040797/146624726-3f84da3f-9787-4522-9144-45ff2ec64222.png)


### Clientes com Veiculos mais novos possuem mais interesse em adquirir o seguro
**Falso.**
- Dos clientes que possuem carros novos **4,37%** possuem interesse.
- Dos clientes que possuem carros usados **29,39%** possuem interesse.
- Dos clientes que possuem carros velhos **17,37%.**

![image](https://user-images.githubusercontent.com/81040797/146606750-29b46b99-45f1-4625-ae1c-d1890c7bc5ab.png)

## Machine Learning Performance
