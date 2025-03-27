# Consulta de CAs de EPIs

Gerenciar Equipamentos de Proteção Individual (EPIs) de maneira eficiente é um desafio para muitas empresas. A falta de controle pode levar a uso indevido, falta de conformidade com normas regulamentadoras, contagens repetitivas, consultas e cadastros demorados. Este projeto foi criado para automatizar a consulta de Certificados de Aprovação (CAs) de EPIs, garantindo que as informações estejam sempre atualizadas e acessíveis de forma prática.

Esta solução acessa automaticamente o site ConsultaCA, coleta os dados sobre os CAs e armazena tudo em uma planilha no Google Drive. Com isso, é possível:

- ✅ Consultar rapidamente a validade de um CA.
- ✅ Manter um banco de dados atualizado dos EPIs aprovados.
- ✅ Facilitar o processo de cadastro e controle de estoque em almoxarifados.
- ✅ Evitar o uso de EPIs vencidos, garantindo conformidade com as normas.


## Observações

1- O script foi projetado para ser executado no Google Colab, pois faz uso do Google Drive para armazenamento dos dados.
2- O O script percorre um intervalo de CAs já determinado, visto que já era de conhecimento o valor maximo, o codigo pode ser ajustado para encontrar a quantidade de valores e percorer de acordo com a quantidade ajustada 
3- A coleta pode levar tempo significativo dependendo do intervalo configurado.
