## Grafos Aula 1

### Definição (Grafos)

```
V = {a,b,c,d,e} (vertices)
E = {ae,be,ce,de,cd,cb} (arestas)
```

### Todo vertice contem um grau:
* d(a) = 1
* d(b) = 2
* d(c) = 3
* d(d) = 2
* d(e) = 4
    
### Exemplo

![image](http://s.glbimg.com/og/rg/f/original/2011/12/09/pontes_grafo_291_218.jpg)

No caso temos os seguintes graus

* d(a) = 3
* d(b) = 4
* d(c) = 3
* d(d) = 3

No caso os vertices com numeros impares de graus é impossivel a solução sem passar pela mesma, pois, existe um grau de entrar, outro de saida e o terceiro fica sem o par de saida; 

### O que é um grafo ( a pergunta de 1 milhão )

Um grafo `G` é consituido de um conjunto `V` não vazio de objetos chamados vertices (ou nós) e um conjuto de `E` de arestas que são pares ordenados de elemetos de `V`. Denotamosassim o grafo por `G(V,E)`

* A)
`V = {v1, v2, v3, v4, v5}`
`E = { (v1,v2), (v2,v3), (v2,v4), (v3,v4) , (v4,v5), (v2,v2), (v1,v2) }`

* B)
`V = {1,2,3,4,5} `
`E = { (1,2), (2,3), (1,4), (1,3) }` 

* C)
`V = {a, b ,c}`
`E = { }`

#### Quando um grafo possui arestas direcionadas?

Um grafo orientado ( ou direcionado ) `G(v,e)` é constitúido por um conjunto `V` não - vazio de objetos ( vértices ou nós ) e um conjunto de par ordenado E (arestas).
Para uma aresta `(Vi,Vj)` é representada por uma linha ligando `Vi` a um `Vj` com um seta apontando para `Vj`

**A OREDEM DA RETA COM A SETA IMPORTA** 

##### Pares ordenados de vértices
##### É um grafo

### Exemplo 2

`V = {v1, v2, v3, v4, v5}`

`E = {(V1,V2),(V1,V3),(V2,V4),(V3,V4),(V4,V5),(V1,V2),(V2,V2)}` 

![grafo2](grafo.png)
