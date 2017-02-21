# Roteiro-2017


| Segunda (Eng. Soft)| Terça (Multi)| Quarta (Grafos/Comp)| Quinta (Micro)| Sexta (CSS)|
|---------|-------|--------|--------|-------|
|[06/02](#eng-aula-1)|  [07/02](#multimídia-aula-1)|[08/02 Compiladores](#compiladores-aula-1) [08/02 Grafos](#grafos-aula-1) | | [10/02](#programacaointenet-aula-1) |
|[20/02](#aula-3-engenharia-de-software)||[15/02 Compiladores](#aula-2-compiladores) [15/02 Grafos](#grafos-aula-2)|||

## Aula 3 - Engenharia de Software

### Distinção entre ES e outras engenharias 
- SW é intangível ;
- Inexistem processos-padrão de SW;
- Projetos de grande porte normalmente são unicos.


### Atividade de gerenciamento:
- Elaboração da proposta;
- Planejamento e desenvolvimento do cronograma;
- Elaboração do custo do projeto;
- Monitoramento e revisão do projeto;
- Selção e abvaliação de pessoas;
- Elaboração de relatórios sobre o projeto.

|Plano| Descição|
| ---| ---|
|Plano de Qualidade | Descreve procedimento e padrão de qualidade|
|Plano de validação | Descreve abordagem recursos e cronogramas|
|Plano de gere3ncimanto de configuração | Descreve procedimento e estruturas sobre o gerencimanto de configurações| 
|Plano de manutenção | Esforços necessários e requisitos para manutenção.|
|Plano de desenvolvimento de pessoal | Descreve como sera trabalhado e as habilidades dos envolvidos|

### Seções do plano de projetos:

- Introdução;
- Organização do projeto;
- Análise de riscos;
- Requisitos de recursos de hardware e software;
- Estrutura analítica;
- Cronograma do projeto;
- Mecanismos de monitoração e elaboração de relatórios.

``` Marcos: Estado do projeto em relação com o tempo de desenvolvimento necessário.```
 
 ### Risco
 
 - Riscos de Projetos - Afeta o cronograma;;
 - Riscos de Produtos - Afeta qualidade e desenpenho;
 - Riscos de negócios - Afeta a organização responsavel pelo projeto.
 
Estratégia de Prevenção 
- reduzir a probabilidade de acontecer.

Estratégia de Minimização 
- Minimizar o que já aconteceu.

## Multimídia Aula 1


Multimédia é a combinação, controlada por computador de pelo menos um tipo de média estática (texto, fotografia, gráfico), com pelo menos um tipo de média dinâmica (vídeo, áudio, animação) (Chapman & Chapman 2000 e Fluckiger 1995). Quando se afirma que a apresentação ou recuperação da informação se faz de maneira multi-sensorial, quer-se dizer que mais de um sentido humano está envolvido no processo, fato que pode exigir a utilização de meios de comunicação que, até há pouco tempo, raramente eram empregues de maneira coordenada, a saber:

### Tipos

- Som (voz humana, música, efeitos especiais);
- Fotografia (imagem estática);
- Vídeo (imagens em pleno movimento);
- Animação (desenho animado);
- Gráficos;
- Textos (incluindo números, tabelas, etc.).


### Características Multimídia 

- Não linearidade;
- Interatividade;
- Imersão.

### Evolução da Multimídia

Pc com Placa de Som e CD-Rom --> Redes Multimidias --> Realidade Virtual

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
                       


## Aula 2 - Compiladores 

Acesso ao material da disciplina:
``migre.me/w455y``
---
Código Fonte ------> Compilador ------> Programa/objeto(assembly)

Analise --- Sintese

Análise:
- Análise Léxica;
- Análise Sintática;
- Análise Semântica.
   ``TABELA DE SÍMBOLO``\
Síntese:
- Geração de código intermediario;
- Otimização de código;
- Geração de código;
 `` Tabela de Erros`` 

### Geração do Código Intermadiário

#### Exemplo:
``` 
                                    x: =(a+c)*(d-10);
``` 

|OPERAÇÃO|OPERAÇÃO|OPERAÇÃO|RESULTADO|
|   ---   |    ---  |    ---  |    - --  |
|    +   |    a   |    c   |  temp1  |
|    -   |   -d   |   10   |  temp2  |
|    *   |  temp1 |  temp2 |  temp3  |
|   :=   |  temp3 |    -   |    x    |

               
