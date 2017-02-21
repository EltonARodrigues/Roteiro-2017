# Compiladores 

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
|    ---   |   ---   |    ---   |    ---    |
|    +   |    a   |    c   |  temp1  |
|    -   |   -d   |   10   |  temp2  |
|    *   |  temp1 |  temp2 |  temp3  |
|   :=   |  temp3 |        |    x    |


