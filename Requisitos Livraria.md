
# Estudo de Caso Sistema de Livraria

O objetivo é criar um sistema que facilite o gerenciamento de clientes, vendedores, pedidos e vendas, garantindo a organização e o suporte às operações comerciais.

# 1. Escopo
O sistema de livraria permitirá que vendedores cadastrem clientes, realizem pedidos, acompanhem perfis de consumo e gerenciem vendas. Os clientes poderão interagir com o sistema para aprovar pedidos e fornecer dados de cadastro.

# 2. Requisitos Funcionais
### Atores Identificados
Vendedor: Usuário responsável por cadastrar clientes, criar pedidos e gerenciar vendas.
Cliente: Usuário que realiza pedidos e aprova vendas.
### Classes Identificadas
Cliente
Vendedor
Perfil de Consumo
Pedido
Produto
Venda Concluída
### Funcionalidades Principais
#### Cadastro de Clientes
O vendedor pode cadastrar novos clientes fornecendo informações básicas como nome, endereço, telefone e e-mail.

#### Cadastro de Pedidos
O vendedor pode registrar pedidos associando-os a um cliente e incluindo os produtos selecionados.

 #### Gerenciamento de Perfil de Consumo
O vendedor pode atualizar o perfil de consumo do cliente com base em compras anteriores.

#### Realização de Vendas
O vendedor pode concluir vendas baseando-se nos pedidos cadastrados.

#### Venda Agregada
O vendedor pode sugerir produtos adicionais durante a finalização de um pedido.

#### Interações do Cliente
O cliente pode realizar um pedido diretamente.
O cliente pode aprovar ou recusar um pedido.
O cliente pode informar ou atualizar seus dados de cadastro.


# 3. Relacionamentos Identificados
#### Cliente - Pedido:
Um cliente pode ter múltiplos pedidos.
#### Vendedor - Pedido:
Um vendedor pode gerenciar múltiplos pedidos.
#### Pedido - Produto:
Um pedido pode conter múltiplos produtos.
#### Cliente - Perfil de Consumo:
Cada cliente possui um perfil de consumo único, atualizado com base nos pedidos realizados.

# 4. Fluxos de Processo
### Fluxo de Cadastro de Cliente:
Vendedor acessa o sistema.
Preenche as informações do cliente.
Confirma o cadastro.

### Fluxo de Criação de Pedido:
Vendedor acessa a lista de clientes.
Seleciona um cliente para associar o pedido.
Adiciona os produtos ao pedido.
Salva o pedido.

### Fluxo de Aprovação de Pedido:
Cliente acessa o sistema.
Revisa o pedido registrado pelo vendedor.
Aprova ou recusa o pedido.
