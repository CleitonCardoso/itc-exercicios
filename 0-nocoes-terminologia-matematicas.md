# Exercícios sobre Noções e Terminologia Matemáticas 

## Conjuntos

1. Examine as descrições formais de conjuntos a seguir de modo que você entenda quais membros eles contêm. Dê uma descrição informal breve de cada junto.

    a. {1, 3, 5, 7, ...}

    b. {..., -4, -2, 0, 2, 4, ...}

    c. {n | n = 2m  para algum m pertencente aos Naturais}

    d. {n | n = m   para algum m onde o resto  da divisão por 2 é igual a 1}

    e. {n | n = m<sup>3</sup>   para algum m pertencente aos Naturais}

    f. {w | w é uma cadeia de 0s e 1s e w é igual ao reverso de w}


2. Forneça descrições formais dos seguintes conjuntos:

    a. O conjunto contendo os números 1, 10 e 100

    b. O conjunto contendo todos os números inteiros que são maiores que 5

    c. O conjunto contendo todos os números naturais que são menores que 5

    d. O conjunto dos cúbitos perfeitos

    e. O conjunto dos números pares

    f. O conjunto dos números divisíveis por 5.

    f. O conjunto contendo a cadeia aba

    g. O conjunto contendo absolutamento nada

3. Seja A o conjunto {x, y, z} e B o conjunto {x,y}.

    a. A é um subconjunto de B?

    b. B é um subconjunto de C?

    c. O que é o A U B?

    d. O que é A ∩ B?

    d. O que é o A x B?

    c. O que é o conjunto das partes de B?

4. Se A tem a elementos e B possui b elementos, quantos elementos estão em AxB ? Explique sua resposta.

5. Se C é um conjunto com c elementos, quantos elementos estão no conjunto das partes de C? Explique sua resposta.

6. Identifique o conjunto de todos os pares cujos os elementos são x e y.

7. Identifique o conjunto de todos os pares cujos os elementos são 1, 2 e 3.

## Sequências

8. Analise as sequências e conjuntos a seguir e verifique se são iguais.


    a. (1, 3)  e (1, 3)

    b. {1, 3, 4, ,1 } e { 1, 4, 3}

    c. (1, 4, 5, 4 ,1 ) e ( 1, 5, 5 ,4)
    
    d. ( 1, 3, 4) e ( 4, 3, 1)

## Funções

9. Seja X o conjunto { 1, 2, 3, 4, 5} e Y o conjunto {6, 7, 8, 9, 10}. A função unária f : X → Y é descrita na tabela a seguir:

        | n | f(n) |
        |---|------|
        | 1 | 6    |
        | 2 | 7    |
        | 3 | 6    |
        | 4 | 7    |
        | 5 | 6    |

    a. Qual é o valor de f(2)?

    b. Quais são o domínio e contradominío de f? 
10. Seja A o conjunto { 1, 2, 3, 4, 5} e B o conjunto {6, 7, 8, 9, 10}. A função binária g : A x B → Y é descrita na tabela a seguir:

        | g | 6  | 7  | 8  | 9  | 10 |
        |---|----|----|----|----|----|
        | 1 | 10 | 10 | 10 | 10 | 10 |
        | 2 | 7  | 8  | 9  | 10 | 6  |
        | 3 | 7  | 7  | 8  | 8  | 9  |
        | 4 | 7  | 9  | 8  | 6  | 10 |
        | 5 | 6  | 6  | 6  | 6  | 6  |

    a. Qual é o valor de g(2,10)?

    b. Quais são o domínio e contradominío de g? 

    b. Qual é o valor de g(2,f(4))? Utilize a função f do exercício anterior.

11. Identifique os conjuntos domínio e contradomínio da seguinte função. Crie a tabela de mapeamento das entradas para a saída.

```java

public int func(int a)
{
    if(a < 0){
        throw new Exception("Invalid parameter informed");
    }
    return a % 4;
}

```

12. Seja o conjunto A {0, 1, 2, 3} o domínio da função f. Identifique o conjunto contradomínio. Crie a tabela de mapeamento das entradas para a saída.

```java

public int f(int a, int b)
{
    return a + b;
}

```

13. Considere a seguinte situação apresentada na imagem abaixo em uma partida jogo da velha. Crie uma função onde dado o movimento do jogador X informe se vencou ou não a partida. Identifique os conjuntos de domínio e contradomínio e a tabela de mapeamento.

 ![alt text](/assets/tic_tac_toe.gif)
