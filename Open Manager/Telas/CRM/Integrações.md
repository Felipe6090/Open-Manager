
Gerenciamento de Integrações do CRM

![[Pasted_image_20250519001948.png]]

### Tabela:
- ID
- Título
- Chave de Integração
- Tipo de Distribuição
- Funil
- Etapa
- Canal de Vendas
- Ativo
- Opções
	- Editar
	- Excluir
## Como funciona a Integração?

Essa integração permite capturar dados de formulários externos e cadastrá-los automaticamente no Open Manager. Além disso, uma negociação será criada no CRM, acionando automações e distribuindo a oportunidade entre os vendedores do funil.

1. Criar uma integração com a API.
2. Copiar a chave da integração na tela de listagem ou edição da integração.
3. Colocar a chave de integração na estrutura de requisição abaixo.

### Exemplo de Requisição Genérica

```
{
	method: 'POST',
	dataType: 'json',
	url: "https://openmanager.com.br:3333/executarIntegracao",
	ContentType: "application/json",
	headers: {
		"empresatoken": "sua-chave-aqui"
	},
	data: {
		cliente: {
			"nome": "Nome do cliente",
			"email": "Email do cliente",
			"telefone": "Telefone do cliente",
			"cpfCnpj": "CPF ou CNPJ do cliente",
			"cpf": "CPF do cliente,
			"cnpj": "CNPJ do cliente"
		},
		chaveIntegracao: "sua-chave-aqui"
	}
}
```

## Criação/Edição

Ao criar ou editar uma integração, um modal no seguinte modelo será aberto:

![[Pasted_image_20250519002249.png]]

Nele é necessário preencher os seguintes dados:
- Funil
- Etapa do Funil
- Título da integração
- Canal de Vendas
- Estimativa de fim da negociação
- Distribuição das negociações
	- Todos os participantes
	- Rodízio
	- Usuário responsável

Após salvar a integração, uma chave será gerada:

```
4e50e91c-9535-4cdf-ae8f-77f21acf278c
```


## Referências
- [[Etapas do Funil]]
- [[Negociação]]
