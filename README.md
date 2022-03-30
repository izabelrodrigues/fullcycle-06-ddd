# Módulo 06 - DDD: Modelagem Tática e Patterns

Entrega desafio update, findById e findAll orders

-----------------------------------|---------|----------|---------|---------|-------------------------------
File                               | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
-----------------------------------|---------|----------|---------|---------|-------------------------------
All files                          |   97.84 |    90.52 |   98.21 |   97.84 |
 domain/entity                     |   96.15 |    92.98 |   97.56 |   96.15 |
  address.ts                       |   80.76 |    63.63 |    87.5 |   80.76 | 19-20,22-23,25-26,28-29,49-50
  customer.ts                      |     100 |      100 |     100 |     100 |
  order-item.ts                    |     100 |      100 |     100 |     100 |
  order.ts                         |     100 |      100 |     100 |     100 |
  product.ts                       |     100 |      100 |     100 |     100 |
 domain/service                    |   93.33 |    83.33 |     100 |   93.33 |
  order-service.ts                 |   89.47 |       75 |     100 |   89.47 | 9-10
  product-service.ts               |     100 |      100 |     100 |     100 |
 infrastructure/db/sequelize/model |     100 |       70 |     100 |     100 |
  customer-model.ts                |     100 |      100 |     100 |     100 |
  order-item-model.ts              |     100 |    66.66 |     100 |     100 | 19,26
  order-model.ts                   |     100 |       75 |     100 |     100 | 27
  product-model.ts                 |     100 |      100 |     100 |     100 |
 infrastructure/repository         |   99.13 |    95.45 |     100 |   99.13 |
  customer-repository.ts           |     100 |      100 |     100 |     100 |
  order-repository.ts              |   98.09 |       90 |     100 |   98.09 | 69-70
  product-repository.ts            |     100 |      100 |     100 |     100 |
-----------------------------------|---------|----------|---------|---------|-------------------------------

Test Suites: 8 passed, 8 total
Tests:       32 passed, 32 total
Snapshots:   0 total
Time:        2.729 s
Ran all test suites.
