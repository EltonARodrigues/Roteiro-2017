# Roteiro-2017


- Engenharia de Software:
    - [Aula 1](#eng-aula-1)

- Multimídia:
    - [Aula-1](#multimídia-aula-1)
 
- Compiladores:
    - [Aula-1](#compiladores-aula-1)

- Grafos:
    - [Aula 1](#grafos-aula-1)
    
- Programação para Internet:
    - [Aula 1](#programacaointenet-aula-1)

## Multimídia Aula 1


Multimédia é a combinação, controlada por computador de pelo menos um tipo de média estática (texto, fotografia, gráfico), com pelo menos um tipo de média dinâmica (vídeo, áudio, animação) (Chapman & Chapman 2000 e Fluckiger 1995). Quando se afirma que a apresentação ou recuperação da informação se faz de maneira multi-sensorial, quer-se dizer que mais de um sentido humano está envolvido no processo, fato que pode exigir a utilização de meios de comunicação que, até há pouco tempo, raramente eram empregues de maneira coordenada, a saber:

### Tipos

- Som (voz humana, música, efeitos especiais);
- Fotografia (imagem estática);
- Vídeo (imagens em pleno movimento);
- Animação (desenho animado);
- Gráficos;
- Textos (incluindo números, tabelas, etc.).

 :shit: Antes era 1k agora é kkkk - CASTILHO,Ediclei :shit:

### Características Multimídia 

- Não linearidade;
- Interatividade;
- Imersão.

### Evolução da Multimídia

Pc com Placa de Som e CD-Rom --> Redes Multimidias --> Realidade Virtual

Johnny Castaway -->  NÃO TEM WILSON --> MAS É DAORA

### Aplicação Multimídia 

- Caixa Eletrônico;
- CD_ROM, DVD-ROM e Blue-Ray;
- DVD-Vídeo;
- Apresentações;
- Web Sites, Blog, Realidade Virtual;
- Quiosques;
- TV interativa, Celulares;
- Games;
- Arte.

---
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


---
## Compiladores Aula 1

Acesso ao material da disciplina:
``migre.me/w455y``
---
Código Fonte ------> Compilador ------> Programa/objeto(assembly)

Analise --- Sintese


Análise:
- Análise Léxica;
- Análise Sintática;
- Análise Semântica.
   ``TABELA DE SÍMBOLO``
Síntese:
- Geração de código intermediario;
- Otimização de código;
- Geração de código;
 `` Tabela de Erros`` 

### Geração do Código Intermadiário

### Exemplo:
``` 
                                    x: =(a+c)*(d-10);
``` 

|OPERAÇÃO|OPERAÇÃO|OPERAÇÃO|RESULTADO|
|   ---  |   ---  |   ---  |   ---   |
|    +   |    a   |    c   |  temp1  |
|    -   |   -d   |   10   |  temp2  |
|    *   |  temp1 |  temp2 |  temp3  |
|   :=   |  temp3 |        |    x    |
                       


