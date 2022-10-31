# javascript

## aula 1: Variaveis

- variaveis:
  
  <Tipo da variavel> + <Nome> = <valor>
  
  o nome da variavel pode ser qualquer um desde que comece com uma letra
  
  em caso de nome composto usar camelCase (**nomeDaVariavel**) ou snake_case (**nome_da_variavel***)
  
  guardam o valor em um espaço de memoria podem ter diversos tipos:
  
  - let
    
    declara um espaço de memoria que pode ter seu conteudo alterado durante o codigo
  
  - const
    
    declara  um espaço de momria, porém, seu conteudo não pode ser alterado durante o codigo

- Operadores
  
  fazem operações entre dados dentro do codigo, são basicamente operções aritmeticas comuns como soma, subtração e multiplicação

## aula 2: estruturas condicionais

A estrutura `if()` é utilizada quando é necessario que o codigo decida entre  duas opções pode ser acompanha de `else if()` `else` caso sejam necessarias mais opções

deve ser colocado na seguinte estrutura:

```javascript
if (condição){
coloque algum codigo aqui
};
else if (outra condição){
 mais codigo aqui codigo aqui
};
else{
 já da pra entender que se coloca codigo entre as chaves não é?
};
```

a `condição` do `if()` deve ser declarada na estrutura:

```javascript
if(<variavel> <operador> <referencia>){...}
```

no caso do `operador` existem alguns caracteres e combinações de caracteres que determinam que tipo de combinação
