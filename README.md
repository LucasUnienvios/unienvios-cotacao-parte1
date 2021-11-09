# Unienvios - Módulo 1

Esse módulo, adiciona os métodos de envio no carrinho e no checkout da aplicação, adiciona também uma tab em Configurações->Vendas->Unienvios para que o admin insira as credenciais da API Unienvios. Além de adicionar os campos extras necessários (CPF, Número, Bairro, Complemento) no checkout, adiciona também atributos no formulario de cadastrado do produto para salvar as dimensões (Altura, Largura, Comprimento e Peso), e por último salva as informações no banco de dados, informações essas necessárias para a criação da cotação que será feita a chamada para a API no outro módulo complementar a esse. https://github.com/LucasUnienvios/unienvios-cotacao-parte2

# Installation

- Copie o conteúdo do repositório para <b>app/code/Unienvios/Cotacao</b>
- Execute o comando: <b>php bin/magento setup:upgrade</b>
- Execute o camando: <b>php bin/magento setup:static-content:deploy pt_BR en_US -f
 </b>  (Use -f for force deploy on 2.2.x or later)
- Agora limpe o cache: <b>php bin/magento cache:flush</b>
