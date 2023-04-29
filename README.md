# apianbima-teste

A aplicação utiliza a API da ANBIMA (Associação Brasileira das Entidades dos Mercados Financeiro e de Capitais) para obter informações dos fundos ICVM 555 no ambiente de teste. Esta API divulga a lista completa de fundos existentes na base do ANBIMA Feed com o resumo de seus respectivos dados. As informações são disponibilizadas pela API com paginação (máximo de 1.000 registros por página). No retorno da API, além da lista de fundos, são informados o número total de fundos e o total de páginas.

É necessário acessar o site: https://admin-developers.anbima.com.br/api-portal/user/register e realizar um cadastro para obter as chaves: Client ID e Client Secret. E a partir dessa api: https://api-sandbox.anbima.com.br/oauth/access-token gerar a chave: "acess-token".

  Informações disponíveis na api:

    codigo_fundo	
    nome_fantasia		
    cnpj_fundo	
    classe_anbima	
    situacao_atual	
    data_inicio_divulgacao_cota
    data_atualizacao
  
  Tecnologias Utilizadas:
  
    HTML/CSS
    JavaScript
    Framework: Bootstrap
    Framework: JQuery
    API da ANBIMA
