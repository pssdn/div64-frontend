#Avaliação técnica Frontend- DIV64

O objetivo desta avaliação é observarmos sua capacidade de observação, atenção a detalhes, organização e metodologias aplicadas. A tarefa é bastante simples: programar um catálogo de produtos para iPad, considerando as possívels variações de viewport e comportamentos do usuário.

Cada categoria disponível na API deve ser renderizada como um carousel exibindo seus produtos. Você poderá consumir os dados dos produtos de duas formas: consultando a collection inteira ou consultando produto a produto. Na collection de categorias você receberá, além dos dados da própria categoria, uma lista com os ids de produtos que a compõe.

Você pode utilizar a tecnologia que preferir para consumir a API. A única exigência é que seja implementada em JavaScript.

O layout está disponível em formato de Illustrator. No pacote acompanham os links e fonts utilizadas, bem como arquivos png para visualização rápida da arte.

##Entregáveis
- HTML e CSS do layout.
- Consumo da API de dados, montando dinâmicamente os catálogos.
- Comportamentos de página: caroussel nas listas de produtos, efeitos hover e transições nos produtos.

##API de dados
A API apenas fornece informações. Qualquer requisição diferente de OPTION, GET ou HEAD será ignorada.

###Categorias
Endpoint: http://env-6651411.jelasticlw.com.br/teste_api/public/categorias

Formato de dados:
```json
[
	{
		"id": 1,
		"slug": "eletronicos",
		"titulo": "Eletrônicos",
		"produtos": [1,2,3]
	},
	{...}
]
```
###Produtos
Endpoint: http://env-6651411.jelasticlw.com.br/teste_api/public/produtos

Formato de dados:
```json
[
	{
		"id": 1,
		"slug": "suqueira-tudo-e-festa",
		"nome": "Suqueira Tudo é Festa",
		"preco": 100.00,
		"thumbnail": "http://env-6651411.jelasticlw.com.br/teste_api/public/thumbnail.jpg",
	},
	{...}
]
```
###Produto
Endpoint: http://env-6651411.jelasticlw.com.br/teste_api/public/produto/:id

Formato de dados:
```json
{
	"id": 1,
	"slug": "suqueira-tudo-e-festa",
	"nome": "Suqueira Tudo é Festa",
	"preco": 100.00,
	"thumbnail": "http://env-6651411.jelasticlw.com.br/teste_api/public/thumbnail.jpg",
}
```

##O que será observado
- Código HTML (semântica, organização, entendimento e componentes da HTML)
- CSS (seletores, propriedades, técnicas, coerência)
- JavaScript (patters, inicialização, inserção no HTML)
- Mobile (tratamento do viewport, transição entre estados do viewport)
- Interação com Git (commits, workflow)

##Método
- Crie um fork deste repositório na sua própria conta.
- Armazene sua aplicação no diretório 'www',
- Gerencie seu repositório da forma que achar conveniente.
- Uma vez concluído, deixe sua última versão na branch master.
- Envie (por email) o link do seu repositório acompanhado de instruções para deploy local, para que possamos avaliar.

##Encorajamos
- Uso de gerenciadores de dependência (Bower, NPM)
- Task runners (Grunt, Gulp)
- Pré-processadores (preferencialmente Sass)
- Gitflow
- Backbone.js

##Desencorajamos
- Pré-compiladores de JavaScript e HTML (Coffescript, HAML...)

##Prazo
- A janela para desenvolvimento inicia-se hoje, 9/03, e extende-se até o dia 14/03 às 9h.
- No dia 14, a partir das 9h, iniciaremos as avaliações e nenhum commit será aceito após esse horário.
- Qualquer dificuldade técnica deve ser informada o quanto antes, para que tenhamos tempo de auxiliar e não prejudicar o desempenho do candidato.

Boa sorte!

Contato:
- (48) 9113-8222
- (48) 3371-3881
- bruno@div64.com