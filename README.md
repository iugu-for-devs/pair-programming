# Caçador de palavras

Seu Joca é um senhor aposentado com o sonho de se tornar programador. Numa tarde
chuvosa de sábado, enquanto resolvia o caça-palavras do jornal, tentou imaginar
como seria um algoritmo para encontrar uma lista de palavras dada uma matriz de
letras. Seguindo as boas práticas aprendidas, imaginou cenários de testes, por
exemplo:

Dada uma matriz

```ruby
[['U', 'V', 'A'],
 ['J', 'U', 'S'],
 ['N', 'G', 'S']]
```

e uma lista de palavras

```ruby
'UVA MANGA'
```

O código deve retornar todas as palavras encontradas, neste caso apenas `'UVA'`.
Se mais palavras forem encontradas, elas devem ser apresentadas em ordem
alfabética.

Além disso, o código deveria ser capaz
de encontrar palavras na horizontal e vertical, em qualquer sentido, ou seja, da
direita para a esquerda ou de baixo para cima, também valem!

Implemente o código do Seu Joca, o caçador de palavras.
