# Programming1_python
Python 

Tasks:
One against one hundred
Water transfer
Paying a sum with coins
LSS Množiny - Destruktivní sjednocení_CZ
LSS Množiny - Destruktivní průnik_CZ
Bases
Průsečík úseček_CZ


One against one hundred:

    You are participating in a competition where you have one hundred opponents. The competition will take place in k stages. In each stage you can eliminate some number     of opponents (always at least one) and you will receive a reward for eliminating them.

    The reward for eliminating 'v' out of 'p' current opponents is

    100,000 * v / p

    rounded down to the nearest integer.

    For example, eliminating 50 out of 100 opponents in the first stage earns you 50,000. Eliminating 30 of 50 opponents in the second stage, you will earn 100,000 *         30/50 = 60,000, and your total reward so far is 110,000. By eliminating the last 20 opponents in the last stage you will earn 100,000 and your total reward will be       210,000.

    Write a program that calculates and prints the maximum possible reward for a given number of stages. On the second output line, write the number of opponents to         eliminate in each individual stage.

    Example:

    Input:
    3
    
    Output:
    280000
    90 9 1
    
Water transfer:

    Let us have three cups of integer sizes a, b, c (a, b, c not greater than 10) containg at the beginning x, y, z of water, respectively.
    We can transfer the water from one cup to other until the cup to is full or the cup from is empty.
    It is not possible to throw the water out as well as take water from some external source.
    Input of the program are numbers a, b, c, x, y, z giving the sizes and starting volumes of cups.

    Program will print the list of all volumes (including zero, if possibble) obtainable by transfers (the whole volume must be containded in one cup) and for each of     those volumes it prints ":" (colon) and minimal number of transfers needed. Volumes would be printed in ascending order.

    Example:

    Input:
      4 1 1  1 1 1
      
    Output:
      0:1 1:0 2:1 3:2
      
Paying a sum with coins:
 
    You are given a certain sum (an integer) and various kinds of coins (at most 20 different kinds). Write out all the ways to pay the given sum, 
    with combinations of larger coins appearing earlier in the output order.

    Read from standard input, and write the result to standard output.

    The input has the following format:

    The first line contains the number of kinds of coins (an integer between 1 and 20).
    The second line contains the value of each kind of coin in descending order (a sequence of positive numbers).
    The third line contains the sum to pay (a non-negative integer).
    Write the output in the following format:

    Each combination of coins should appear on its own line.
    On each line, write the numbers in order fro! m largest to smallest, separated by a space.
    Write the lines in order from largest to smallest in lexicographic order (see the example below).
    You may assume that each line is at most 256 characters long (it will fit in a Pascal string).
    
    Example:

    input:
    3
    5 2 1
    9
    
    output:
    5 2 2
    5 2 1 1
    5 1 1 1 1
    2 2 2 2 1
    2 2 2 1 1 1
    2 2 1 1 1 1 1
    2 1 1 1 1 1 1 1
    1 1 1 1 1 1 1 1 1
    
LSS Množiny - Destruktivní sjednocení_CZ:

    Napište funkci, která dostane jako parametr dvě množiny representované jako vzestupně uspořádané jednosměrné lineární spojové seznamy a 
    vrátí jejich DESTRUKTIVNÍ SJEDNOCENÍ.
    Destruktivní znamená, že funkce nebude vytvářet žádné nové prvky, ale výsledný seznam vytvoří pouze z prvků původních seznamů.
    Sjednocení znamená sjednocení, tedy pokud se nějaká hodnota vyskytovala v obou seznamech, ve výsledném seznamu bude pouze jednou.
    Výsledný seznam musí být zase vzestupně uspořádán.
    Úlohu řešte pouze pomocí lineárních spojových seznamů, pro řešení tedy nepoužívejte žádné datové struktury jako je množina, seznam a podobné.
    Pro vytvoření řešení použijte šablonu, která obstará načtení vstupu i výpis výstupu, takže jediné, co potřebujete udělat, je vyplnit tělo funkce UnionDestruct.
   
   
LSS Množiny - Destruktivní průnik_CZ:

    Napište funkci, která dostane jako parametr dvě množiny representované jako vzestupně uspořádané jednosměrné lineární spojové seznamy a 
    vrátí jejich DESTRUKTIVNÍ PRŮNIK.
    Destruktivní znamená, že funkce nebude vytvářet žádné nové prvky, ale výsledný seznam vytvoří pouze z prvků původních seznamů.
    Průnik znamená průnik, tedy pokud se nějaká hodnota vyskytovala v obou seznamech, bude i ve výsledném seznamu (pouze jednou), jinak ne.
    Úlohu řešte pouze pomocí lineárních spojových seznamů, pro řešení tedy nepoužívejte žádné datové struktury jako je množina, seznam a podobné.
    Pro vytvoření řešení použijte šablonu, která obstará načtení vstupu i výpis výstupu, takže jediné, co potřebujete udělat, je vyplnit tělo funkce                       IntersectionDestruct.
   
   
Bases:

    Write a program that first reads two pairs of integers from standard input. Each pair contains a base (from 2 to 10) and a number written in that base.
    Next, read an integer indicating the base in you should print the sum, difference, product and integer quotient of these two numbers, 
    with each of these values on a separate line.
    The numbers' values (but not necessarily their written representations, e.g. in binary!) will fit into a two-byte integer.

    Example:

    Input:
    5 11 2 101 7

    Output:
    14
    1
    42
    1
    
    
Průsečík úseček_CZ:

    Vstupem programu je osm celých čísel Ax, Ay, Bx, By, Cx, Cy, Dx, Dy představujících souřadnice čtyř bodů A, B, C, D v Euklidovské rovině. 
    Čísla jsou zapsaná na jedné řádce a oddělená vždy jednou mezerou.
    Program vytiskne odpověď ANO, pokud úsečky AB a CD mají nějaký společný bod, nebo NE, pokud úsečky AB a CD nemají žádný společný bod.

    Například pro vstupní hodnoty: 0 0 1 1 0 1 1 0 bude odpověď ANO.
