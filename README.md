# DESAFIO-WIND

1 - Entrar no site http://dados.tce.rs.gov.br/organization/tribunal-de-contas-do-estado-do-rio-grande-do-sul e localizar o Item Licitações Consolidado 2022, navegar até o link de download e baixar o arquivo. 

![image](https://user-images.githubusercontent.com/98180262/173396529-686a3a06-60bf-48df-a204-dea8fe5508f1.png)

2 – Manter somente os arquivos item.csv e licitacoes.csv na raiz.

3 – Filtrar licitacoes.csv com DT_ABERTURA maior que 01 de maio de 2022.

4 – Criar diretórios com a estrutura CD_ORGAO - CD_TIPO_MODALIDADE - NR_LICITACAO - ANO_LICITACAO.

<b>OBS¹: Somente as primeiras 30(trinta) ocorrências.<b><br>
<b>OBS²: As imagens são apenas para exemplificação, desta forma, não necessariamente seu retorno será igual ao exemplo.<b>

![image](https://user-images.githubusercontent.com/98180262/171285203-b45ea2a0-b5b3-4fa1-8a9e-50f6eb023de7.png)
 
5 – Criar arquivo link.txt com a informação da coluna LINK_LICITACON_CIDADAO do item respectivo com base no arquivo licitacoes.csv.

![image](https://user-images.githubusercontent.com/98180262/171285240-1c841e0b-8545-4e66-b1d3-53ddfb1cb514.png)
 
6 – Criar arquivo itens-licitacao.csv dentro do diretório da licitação respectiva com os itens da licitação com base no arquivo item.csv.
Combinar CD_ORGAO, NR_LICITACAO, ANO_LICITACAO, CD_TIPO_MODALIDADE para retornar os itens da licitação.

![image](https://user-images.githubusercontent.com/98180262/171285273-e25123e4-b9fa-4822-893b-a748aaf11e6c.png)
