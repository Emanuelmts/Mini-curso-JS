# Mini-curso-JS
# Parte 1

  ## Nesse repositório, estarei digitando e estudando sobre tecnologia e JavaScript.
  
Ao construir um aplicativo/site/software, existem dois tipos de "trabalhos": Construir o visual (interface) e como se dará seu comportamento.
Para a construção de interfaces, duas tecnologias comumente usadas juntas do JavaScript são **HTML** e **CSS**.

Para que nossas aplicações se comporte da maneira que quisermos, devemos dar instruções ao computador, criando uma **sequência de passos** informando exatamente o que queremos que aconteça em cada pedacinho do nosso programa.
À essa sequência, dá-se o nome de **algortimo**.

Para imaginarmos, um professor quer ajuda para calcular a média de um aluno. Supomos que a média é dada por 3 notas com os pesos 3, 3 e 4, a sequência de passos se pareceria com isso:

```
Algoritmo media(recebe nota prova 1, nota prova 2 e nota prova 3)
- Multiplica a nota 1 por peso 3
- Multiplica a nota 2 por peso 3
- Multiplica annota 3 por peso 4
- A média é dada pela soma das notas e dividida por 10
- Tem-se a resposta da média
```

Assim, criando esse algoritmo, esperamos uma saída:

```
Executar algoritmo media(com notas 5, 5 e 10) => resposta é 7
```

Usarei JavaScript para criar os códigos.


# Parte 2

Agora é começar a criar algoritmos com JS

Começamos com um algoritmo de somar dois números

```
Algoritmo somar (recebe num1 e num2)
  - soma num1 com num2
  - retorna essa soma
```

Para representar esse algoritmo em JavaScript, escrevemos:

```JavaScript
function somar(num1, num2) {
  let soma = num1 + num2
  return soma
}
```
