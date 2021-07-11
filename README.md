# orcamento-sp-webservice

1) Este notebook demonstra como consultar as informações de execução financeira e orçamentária disponibilizados em web service da Secretaria da Fazenda e Planejamento do Estado de São Paulo.
2) Uma vez que o web service fornece resposta no formato XML, utilizou-se a biblioteca Beautiful Soup para extrair as informações das tags de interesse.
3) Na sequência, fez-se uso do Pandas para a criação do DataFrame, exploração dos dados e gravação de arquivo Excel.
4) No exemplo, a consulta foi feita para o TJSP, ano de 2021 (atualiz. até 11 jul.).
