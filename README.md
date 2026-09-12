## Contexto
Alguma coisa

## Diagnóstico da origem
Na tabela de pedidos e lojas, foram identificadas 50 grafias distintas para nomes de lojas, indicando falta de padronização, além de 18 grafias distintas de categorias. Em relação à integridade dos dados de vendas, existem 1575 pedidos sem código de loja preenchido, o que representa aproximadamente 39% do total, e outros 3 pedidos sem nome de loja, os quais foram direcionados para o identificador padrão -1.
Por fim, a análise do script revela que existem 6.033 marcos de processo em branco, que correspondem a processos em aberto e deverão assumir o valor de dias como NULL na modelagem, sendo eles: Dt Separacao Estoque: 1077; Dt_Despacho_Transportadora: 1665; DtEntregaCliente: 1953; DtNotaFiscal: 1338.