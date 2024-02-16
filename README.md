# controle_de_estoque
Prática Fundamentos de Banco de Dados - Descomplica2024

###

## Requisitos Funcionais:

- Cadastro de produtos: O sistema deve permitir o cadastramento de novos produtos.
- Atualização de produtos: Deve ser possível atualizar as informações dos produtos já cadastrados.
- Listagem de produtos: O sistema deve possibilitar a visualização de todos os produtos cadastrados.
- Manutenção de fornecedores: Capacidade de adicionar, atualizar e listar informações dos fornecedores.
- Registro de entradas de estoque: Permitir o registro das entradas de produtos no estoque, incluindo informações como quantidade, data e fornecedor.
- Registro de saídas de estoque: Possibilitar o registro das saídas de produtos do estoque, incluindo informações como quantidade, data e destino.
- Emissão de relatórios de estoque: Capacidade de gerar relatórios sobre o status atual do estoque, incluindo quantidade disponível de cada produto.

## Requisitos Não Funcionais:

- Segurança: O sistema deve garantir a segurança dos dados, com acesso restrito por meio de autenticação.
- Desempenho: Deve ser capaz de lidar com um volume considerável de transações sem comprometer o desempenho.
- Usabilidade: Interface intuitiva e fácil de usar para os usuários finais.
- Disponibilidade: O sistema deve estar disponível durante o horário comercial para que os usuários possam acessá-lo conforme necessário.
- Escalabilidade: Capacidade de expansão para atender a um aumento na demanda ou adição de novos recursos no futuro.


## Entidades Principais:

- Produto
- Fornecedor
- Entrada de Estoque
- Saída de Estoque


## Relacionamentos:

- Um Produto é fornecido por um Fornecedor (Relacionamento 1:N).
- Uma Entrada de Estoque está relacionada a um Produto (Relacionamento 1:N).
- Uma Saída de Estoque está relacionada a um Produto (Relacionamento 1:N).


## Chaves:

- Produto: Chave Primária - ID do Produto
- Fornecedor: Chave Primária - ID do Fornecedor
- Entrada de Estoque: Chave Primária - ID da Entrada; Chave Estrangeira - ID do Produto
- Saída de Estoque: Chave Primária - ID da Saída; Chave Estrangeira - ID do Produto

Agora, vamos desenhar o Modelo Entidade-Relacionamento (MER):

![controle-de-estoque](https://github.com/alexsabrasil/controle_de_estoque/assets/113733583/843c2f07-646d-4186-8737-8d88fef7b456)


