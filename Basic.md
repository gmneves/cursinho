# Trabalhando com diretórios

O sistema operacional Linux possui uma estrutura hierárquica, com diretórios e subdiretórios, com atributos e permissões específicas, e com propósitos distintos.

Nota: No Linux, com poucas exceções, parâmetros simples compostos por apenas 1 caracter e sem argumentos adicionais podem ser descritos de forma encadeada, ou separada, como exemplificado abaixo.

Básico de listagem e navegação
--

Verificar diretório atual
--
- Comando: **pwd**

"Print Working Directory"  
Comando somente leitura, utilizado apenas para exibir o diretório em que o operador está posicionado.  

Exemplo de execução
--
```console
pwd
```

Listagem de diretórios
--

- Comando: **ls**

"List"  
Comando somente leitura, utilizado para listar conteúdo de diretórios, pode ser utilizado com ou sem parâmetros, que modificam a saída.  


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
