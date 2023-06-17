# Trabalhando com diretórios

O sistema operacional Linux possuí uma estrutura hierárquica, com diretórios e subdiretórios, com atributos e permissões específicas, e com propósitos distintos.

Básico de listagem e navegação
--

Listagem de diretórios
--

- Comando: ls

Comando somente leitura, utilizado para listar conteúdo de diretórios, pode ser utilizado com ou sem parâmetros, que modificam a saída.

De forma geral no Linux, parâmetros simples que são compostos por apenas 1 caracter e sem argumentos adicionais podem ser descritos de forma encadeada, ou separada.

Exemplos de execução:
--

- Lista
	```console 
	ls -l
	```

- Lista com ordenação reversa
	```console 
	ls -lr 
	ls -l -r
	```

- Lista com ordenação por tamanho decrescente (maior tamanho para o menor tamanho)
	```console 
	ls -lS
	ls -l -S
	```
	
- Lista com ordenação por data de modificação decrescente (mais novo para o mais antigo)
	```console 
	ls -lt
	ls -l -t
	```
	
É possível também somar os parâmetros para, por exemplo, alterar a ordenação de decrescente para crescente

- Lista com ordenação por tamanho crescente (menor tamanho para o maior tamanho)
	```console 
	ls -lSr
	ls -l -S -r
	```
	
- Lista com ordenação por data de modificação crescente (mais antigo para o mais novo)
	```console 
	ls -ltr
	ls -l -t -r
	```
