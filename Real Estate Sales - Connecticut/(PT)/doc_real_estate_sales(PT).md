# Mercado Imobiliário - Connecticut
A base de dados pode ser encontrada em [data.ct.gov](https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2020-GL/5mzw-sjtu)

## Contexto
> O Escritório de Política e Gestão de Connecticut mantém uma lista de todas as vendas de imóveis com preço de venda de US$ 2.000 ou superior que ocorrem entre 1º de outubro e 30 de setembro de cada ano no estado de Connecticut. Para cada registro de venda, o arquivo inclui: localidade, endereço do imóvel, data da venda, tipo de imóvel (residencial, apartamento, comercial, industrial ou terreno baldio), preço de venda e avaliação do imóvel.

> Os dados são coletados de acordo com os Estatutos Gerais de Connecticut, seções 10-261a e 10-261b: https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261a e https://www.cga .ct.gov/current/pub/chap_172.htm#sec_10-261b.

> As vendas anuais de imóveis são relatadas por ano da lista geral (de 1º de outubro a 30 de setembro de cada ano). Por exemplo, as vendas do GL 2018 são de 01/10/2018 a 30/09/2019.

## Conteúdo

- listyear: Ano em que o imóvel foi colocado à venda

- daterecorded: Data em que a venda foi registrada localmente

- cidade: nome da cidade

- endereço: endereço residencial

- valor avaliado: Valor do imóvel utilizado para avaliação fiscal local

- saleamount: valor pelo qual o imóvel foi vendido

- salesratio: relação entre o preço de venda e o valor avaliado

- propertytype: Tipo de imóvel incluindo: Residencial, Comercial, Industrial, Apartamentos, Vago, etc.

- residencialtype: Indica se o imóvel é residencial unifamiliar ou multifamiliar

- observações: Observações do avaliador

- geo_coordenadas: coordenadas lat/lon

- opm_remarks: comentários do OPM

- nonusecode: Código de venda não utilizável normalmente significa que o preço de venda não é confiável para uso na determinação do valor de uma propriedade.

### Descrição dos códigos da coluna 'nonusecode':

| Código | Categoria                   | Descrição                                                                                                       |
|--------|-----------------------------|-----------------------------------------------------------------------------------------------------------------|
| 01     | FAMILY Sale                | Venda entre membros da mesma família.                                                                           |
| 02     | LOVE AND AFFECTION         | Venda na qual "Amor e afeição" fazem parte do preço de venda, conforme declarado na escritura.                 |
| 03     | INTER CORPORATION          | Vendas entre uma corporação e acionista, subsidiária, afiliada ou outra corporação.                             |
| 04     | CORRECTING DEED            | Transferências por conveniência; por exemplo, vendas para corrigir defeitos no título, criar sobrevivência, etc.|
| 05     | DEED DATE                   | A data em que a escritura foi assinada ou a data do acordo é mais de seis meses antes da data de avaliação de 1º de outubro do ano corrente.|
| 06     | PORTION OF PROPERTY         | Vendas de propriedades que transferem apenas uma parte da propriedade avaliada como uma unidade, por exemplo, uma divisão.|
| 07     | CHANGE IN PROPERTY          | Vendas de propriedades substancialmente melhoradas ou alteradas após a data de avaliação.                        |
| 08     | PART INTEREST               | Vendas de um interesse indiviso ou parte em propriedade real. Para cooperativas, use este código.               |
| 09     | TAX SALE                    |                                                                                                                 |
| 10     | A WILL                      | Transferências feitas de acordo com um artigo do testamento do falecido, para um beneficiário que é um herdeiro.  |
| 11     | COURT ORDER                 | Venda judicial proveniente de uma ordem do tribunal.                                                            |
| 12     | NON BUILDABLE LOT           | Venda de um lote não edificável para um proprietário vizinho.                                                   |
| 13     | BANKRUPCY                   | Venda em processo de falência, administração judicial ou cessão em benefício dos credores, dissoluções e liquidações.|
| 14     | FORECLOSURE                 | Venda de uma propriedade executada judicialmente.                                                              |
| 15     | GOVERNMENT AGENCY           | Venda para ou de uma agência governamental (local, estadual ou federal).                                        |
| 16     | CHARITABLE GROUP             | Venda para ou de uma organização beneficente, educacional, benevolente ou religiosa.                             |
| 17     | TWO TOWNS                   | Venda de um lote de propriedade avaliado ou localizado em mais de uma cidade ou estado.                           |
| 18     | IN LIEU OF FORECLOSURE      | Transferência para bancos, companhias de seguros, associações de poupança e empréstimo, companhias hipotecárias ou qualquer outro detentor de ônus, quando a transferência é feita em vez de uma execução hipotecária.|
| 19     | EASEMENT                    | Vendas, como para ou de empresas de serviços públicos, empresas de eletricidade, telefone, gás ou indivíduos (direito de passagem).|
| 20     | CEMETERY                    | Venda de lote de cemitério.                                                                                    |
| 21     | PERSONAL PROPERTY EXCHANGE  | Venda de propriedade real em troca de qualquer ativo que não seja dinheiro, como outras propriedades, ações ou títulos.|
| 22     | MONEY AND PERSONAL PROPERTY | Venda de propriedade real, que inclui móveis, máquinas, equipamentos, inventários ou fundo de comércio, quando o valor em dinheiro desses itens é indeterminado. (Observação: Esta categoria não se aplica a eletrodomésticos ou unidades 'embutidas', que normalmente estão incluídas na venda. Por exemplo, fogão, lava-louças, carpete, etc.)|
| 23     | ZONING                      | Venda de propriedade cujo valor foi influenciado significativamente por mudanças de zoneamento desde a última data de avaliação.|
| 24     | PLOTTAGE                    | Combinação de dois ou mais terrenos sob uma única propriedade quando cada um é considerado separadamente.       |
| 25     | OTHER REASONS               | A razão está significativamente acima ou abaixo. Venda que, por algum motivo que não seja as categorias enumeradas acima, é considerada não ser uma transação entre um comprador disposto (não obrigado a comprar) e/ou um vendedor disposto (não obrigado a vender). Explique em OBSERVAÇÕES.|
| 26     | REHABILITATION DEFERRED     | (Seção 12-65c a 12-65f C.G.S)                                                                                |
| 27     | Redução Avaliação Fundação Deteriorada | Usado apenas quando a propriedade sendo vendida tem uma redução na avaliação devido a um problema de fundação deteriorada.|
| 28     | Avaliação de Uso             | Código 600 Venda de uma propriedade que está sob avaliação de uso (agricultura, floresta, espaço aberto: Seção 12-107a-f).|
| 29     | Sem Consideração             |                                                                                                                 |
| 30     | Leilão                       | Vendas de propriedade em um leilão público ou privado.                                                         |
