# PI3 -  Sistema para Aluguel de Veículos

![Feito com Java EE](https://img.shields.io/badge/made%20with-java%20ee-red.svg)
![Projeto Integrador 3](https://img.shields.io/badge/projeto%20integrador-III-lightgrey.svg)

**Fundação Visconde de Cairu | ADS | Desenvolvimento de Software II | Pré-Matutino**

**Grupo de programadores:**

[Manoel Ribeiro](https://github.com/ManoelRibeiro-)

[Alisson Santos](www.google.com)

[Gelvan Fernandes](www.google.com)

[Denis Amaral](www.google.com)

[Rafael Francisco](www.google.com)

# Requisitos:

## Classes:

	* `Veículo`
	* `Aluguel`
	* `Cliente`
	* `Usuário`

### Atributo das Classes:

**Veículo:**

	`numero - String`
	`placa - String`
	`fabricante - String`
	`modelo - String`
	`anoModelo - int`
	`qtdPorts - int`
	`Acessorios -  String`

**Aluguel:**

	`idAluguel - int`
	`veiculo - Veiculo`
	`dataAluguel - Date`
	`dataEntrega - Date`
	`cliente - Cliente`
	`entregue - char`
	`observacao - String`
	`valorPago - Decimal`

**Cliente:**

	`nomeCliente - String`
	`endereco - String`
	`uf - String`
	`telefone - String`
	`cpf - String`
	`e_mail - String`

**Usuário:**

	`Nome - String`
	`Cargo - String`
	`Login - String`
	`Senha - String`
	`e_mail - String`

## Telas específicas:
	* Deverá existir uma tela para consultar o faturamento dado um período específico

	* Deverá existir uma tela para consultar os veículos que não foram entregues no prazo

	* Deverá existir uma tela para mostrar uma lista de quais veículos estão alugados

## Funções do usuário:
	* Cadastrar, consultar e excluir Clientes

	* Cadastrar, consultar e excluir Veículos

	* Cadastrar, consultar e excluir Alugueis

## Observações:
	* Não pode alugar um veículo que já foi alugado e não entregue

	* O sistema deve acusar se um veículo foi alugado

	* O cliente e o veículo devem existir para gravar o aluguel
