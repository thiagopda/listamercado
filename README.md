# listamercado
Repositorio da API da lista do mercado feito em Java com Springboot

# Sistema Lista Mercado
## Requisitos
	- Ser capaz de gerenciar várias listas de mercado (e marca-lá como concluída ou não).
	- Ser capraz de criar produtos e consulta-los
	- Ser capaz de incluir itens nas listas e especificar sua quantidade bem como marcar se item já foi comprado ou não
	- Ser capaz de tribuir valores aos itens comprados para depois ter uma gestão ter uma gestão dos curtos da lista.
	- Ser capaz de adicionar quantidades (Kg. unidades, litros etc).

## Casos de Uso - Produto
### Cadastrar produtos
	- Informar o nome de um determinado produto e o sistema o armazena no Banco de dados.

### Consultar produtos
	- Informar palavras chaves para consultar ou mesmo buscar produtos a partir de uma lista.

### Alterar dados de produtos
	- Alterar o nome de um produto e termos sua efetivação no banco de dados
--------------------------------------------------------

## Casos de uso - Listas
### Criação de listas
	- Criar uma nova lista inserindo a data e local onde foi feita a compra (nome do supermercado/feira etc).

### Apagar uma lista
	- Remover umja lista que foi criada por engano ou apagar todos os intens criados nela.

### Inserção de itens 
	- Criar um item associando a uma lista e a um produto, bem como deixar disponível a possibilidade de modificar quantidade e preço que foi pago.

### Alteração do item
	- Alterar quantidade, preço pago e status.

### Remoção de item
	- Poder removr um item que foi cadastrado na lista

### Fechamento
	- Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprados.
