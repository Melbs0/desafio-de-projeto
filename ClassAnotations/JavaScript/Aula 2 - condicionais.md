# aula 2: estruturas condicionais

A estrutura `if()` é utilizada quando é necessario que o codigo decida entre duas opções pode ser acompanha de `else if()` `else` caso sejam necessarias mais opções

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

no caso do `operador` existem alguns caracteres e combinações de caracteres que determinam que tipo de comparação será feita entre os dois dados:

- `!=` (não igual)  sinalizara se os dados incuidos na comparação são diferentes um do outro

- `==` (igual)sinaliza se os dados são iguais em valores

- `===` (estritamente igual) sinaliza se os dados são iguais em valores e tipos

- `<` (menor que)  e `>` (maior que) sinaliza true caso o valor a esquerda do operador seja, respectivamente, menor ou maior que o dado a direita

- `<=` (menor igua que) e `>=` (maior igual que)  sinaliza true caso o valor a esquerda do operador seja, respectivamente, menor, maior ou igual que o dado a direita