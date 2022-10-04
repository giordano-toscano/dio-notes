# Variáveis, Tipos de Dados e Operadores Matemáticos em Java

## 1. Conceituação e criação

Conceituação:

> Uma variável é um espaço na memória do computador, onde se pode guardar valores.

Existem 4 tipos:

- Instância: objeto<br>
- Classe: classe<br>
- Local: dentro de métodos<br>
- Parâmetro: na assinatura do método

Padrão de definição:


```
<?visibilidade?><?modificador?> tipo nome <?=valorInicial?>;
```


**visibilidade**: "public", "protected" e "private"<br>
**modificador**: "static" e "final"<br>
**tipo**: tipo de dado<br>
**nome**: nome que é fornecido a variável<br>
**valorInicial**: um valor inicial, caso se deseje

## 2. Tipos de dado

Conceituação

> São os valores e, consequentemente, as operações que as variáveis podem assumir e sofrer, respectivamente.

Tipificação:

- Estática (forte) vs Dinâmica (fraco)
- Primitivo vs Composto

De forma geral e resumida, temos as seguintes opções de tipos:

- Textual
- Numeral
- Lógico
- Objeto

Tabela de valores default para cada tipo de dado:

<img src="../images/Default Values For Each Data Type.JPG" width="400"/>

## 3. Operadores Aritméticos

Conceituação:

> São símbolos especiais quais são capazes de realizar ações específicas em um, dois ou mais operandos e, em seguida, retornar um resultado.

Tipos:
- Pós-fixado: exp++ ou exp--
- Pré-fixado: ++exp ou --exp
- Aritmético: +, -, *, / e %
- Atribuição: =, +=, -=, *=, /= e %= 

| Operador       | Precedência           |
| -------------- | --------------------- |
| Pós-fixado     | exp++, exp--          |
| Pré-fixado     | ++exp, --exp          |
| Multiplicativo | *, /, %               |
| Aditivo        | +, -                  |
| Atribuição     | =, +=, -=, *=, /=, %= |

## 4. Conversões (casting)

Conceituação:

> É a transformção de uma variável de tipo menos específico para um tipo mais específico ou vice-versa.

Tipos:

- Upcast (implícito)
- Downcast (explícito)

Tabela de conversões:

<img src="../images/Upcast And Downcast Table.JPG" width="500"/>


















