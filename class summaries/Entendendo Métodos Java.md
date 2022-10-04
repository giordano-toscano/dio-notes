# Entendendo Métodos Java

## 1. Criação

I) Conceituação

> É uma porção de código (sub-rotina) que é disponibilizada por uma classe. Este é executado quando é feita uma requisição a ele. São responsáveis por definir e realizar um determinado comportamento.

II) Padrão de definição:

```
<?visibilidade?> <?tipo?> <?modificador?> retorno nome (<?parâmetros?>) <?exceções?> corpo
```

**visibilidade**: "public", "protected" ou "private"<br>
**tipo**: concreto ou abstrato<br>
**modificador**: estático, não estático ou "final"<br>
**retorno**: tipo de dado ou "void"<br>
**nome**: nome que é fornecido ao método<br>
**parâmetros**: parâmetros que pode receber<br>
**exceções**: exceções que pode lançar<br>
**corpo**: código que possui ou vazio

III) Conceitos inerentes aos métodos:

- **Assinatura** - é a forma de identificar unicamente o método (_assinatura = nome + parâmetros_)
    
    Exemplo:
    
    Método: `public double calcularTotalVenda (double precoItem1, double precoItem2){...}`
    
    Assinatura: `calcularTotalVenda (double precoItem1, double precoItem2)`

- **Construtor e Destrutor** - são métodos especiais usados na Orientação a Objetos

- **Mensagem**: é o ato de solicitar ao método que o mesmo execute. Esta pode ser direcionada a um objeto ou a uma classe.

- **Passagem de parâmetros**:
  - Por valor (cópia)
  - Por referência (endereço)


## 2. Sobrecarga

I) Conceituação

> É a capacidade de definir métodos para diferentes contextos, mas preservando seu nome.

II) Criação

```
converterParaInteiro(float f);
converterParaInteiro(double d);
converterParaInteiro(float f, RoundType rd);
converterParaInteiro(RoundType rd, float f);
```

## 3. Retornos