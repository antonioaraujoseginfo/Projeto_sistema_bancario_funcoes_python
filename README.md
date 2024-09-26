# Sistema Bancário

Este é um sistema bancário simples desenvolvido em Python, que permite a criação de clientes e contas, bem como a realização de operações como depósitos, saques e consultas de extrato.

## Funcionalidades

- **Cadastro de Clientes**: Adicione novos clientes ao sistema.
- **Criação de Contas**: Crie contas correntes para os clientes.
- **Depósito**: Realize depósitos nas contas.
- **Saque**: Realize saques, respeitando limites.
- **Extrato**: Consulte o extrato de transações da conta.
- **Listagem de Contas**: Liste todas as contas cadastradas.

## Interaja com o menu

- O sistema exibirá um menu com as opções disponíveis. Siga as instruções para realizar as operações desejadas.

## Estrutura do Código

- **Cliente**: Classe base que representa um cliente.
- **PessoaFisica**: Subclasse que representa um cliente do tipo pessoa física.
- **Conta**: Classe base para contas bancárias.
- **ContaCorrente**: Subclasse que representa contas correntes.
- **Historico**: Classe para armazenar o histórico de transações.
- **Transacao**: Classe abstrata base para transações.
- **Deposito/Saque**: Classes específicas para transações de depósito e saque.

## Exemplo de Uso

Após iniciar o sistema, você pode criar um novo cliente e, em seguida, criar uma conta para ele. Você pode então realizar depósitos e saques, além de consultar o extrato da conta.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
