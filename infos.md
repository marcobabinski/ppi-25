# Infos sobre a PPI/Análise de Dados:

## Produtos
### O que são os códigos:
- Serviços: 63998, 64003, 63997, 63996, 63994, 63995
- Fretes: 1107, 1124, 1135, 1152, 1071, 1111, 1078, 48018
- Produtos: os demais

## Notas
### O que são os campos
- Data: data de emissão da nota
- Controle: registro de controle da nota (considere com o número da NF)
- Cliente: codigo do cliente
- Municipio: municipio do cliente
- Bairro: bairro do municipio do cliente
- ProCod: codigo do produto
- NumSeq: sequencial dos itens por nota
- Quantidade: quantidade do produto
- Preco: preço unitário do produto 

## Clientes
### Casos especiais:
- Cliente 99999: genérico para vendas sem CPF

## Relatório
### Pontos requeridos pela cotrifred:
- [ ] Concentração de clientes por bairro (considerando que para o supermercado são locais de entrega);
- [ ] Curva ABC das vendas dos produtos; e
- [ ] Identificar os itens "não movimentados", considerando apenas a familia 1 (MERCADO).

### Organização da apresentação
#### O que precisa fazer:
- [ ] Revisar agrupamento dos bairros
- [ ] Tirar as vendas com produtos de frete e serviço

#### Escopo da apresentação
- Considerando somente FW e seus bairros
- Dados de clientes somente para aqueles que informam CPF

#### Pontos da apresentação
- Porcentagem de vendas que informam CPF
  - Mostrar o quão grande é o volume de vendas sem cpf que é incapaz de traçar um perfil
  - As vendas sem CPF são um aglomerado indistinguível.
  - Mostrar em dinheiro também esse volume
  - Por que as pessoas não informam CPF? (é de mau gosto, sugestão: só pontuar a quantidade de vendas sem cpf mesmo)
    - É um processo lento/chato?
    - Elas não querem “vender” seus dados?
    - As pessoas não conhecem os benefícios? (esse é interessante comentar)
- Porcentagem que retorna/porcentagem de que retorna múltiplas vezes
  - Histograma
- Número total de clientes diferentes
- Vendas por bairro
  - Por valor e por quantidade
  - Mapa de calor
- Vendas por data
  - Período do ano com mais vendas
  - Mostrar em valores numéricos
- Principais produtos (uns 20 sla)
  - Listar eles e o valor arrecadado
  - Por taxa de aparição em vendas e por denhero
  - Dias da semana que eles saem
  - Período do ano que eles saem
