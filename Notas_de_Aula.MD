# LINGUAGEM C

## Ciclo do desenvolvimento
    Edi��o do c�digo fonte
    Compila��o do programa
    Linkagem do objeto
    Execu��o do programa
<br>

## Anatomia de um programa
    O programa � formado por uma ou mais fun��es, e cada fun��o possui um nome exclusivo e corresponde � um bloco de c�digo, delimitado por um par de chave {}
    Cont�m um conjunto de declara��es, express�es, comando de controle e chamadas � outras fun��es
<br>

## Alguns comandos
### Contrabarra (\\)
    Tem a fun��o de "escape" quando usada isolada

    Usos:
    \n - Nova linha
    \t - Tabula��o horizontal

### Coment�rios (/)
    / - One line
    /* - Multiline
    /** - Documentation

### Sizeof
    Retorna o tamanho da vari�vel

### Constantes
    O nome deve ser declarado todo em MAI�SCULO
<br>

## TIPOS DE DADOS
| Dado | Range |
| --- | --- |
| char | -128 a 127 |
| unsigned char | 0 a 255 |
<br>

## CAST ("convers�o")
    a = 10, b = 3

    int x = a / b >>> 3
    double x = a / b >>> 3.0

double x = a / *(double)* b >>> 3.33
