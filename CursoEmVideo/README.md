# Exercícios do Curso de Python 3 do Curso em Vídeo
**Descrição:** Este documento tem como objetivo explicar o que foi feito em cada exercício, descrevendo de forma clara o que cada comando faz e dando informações extras, como as diferentes formas que podemos solucionar um mesmo problema utilizando a linguagem **Python**.

---

### Ex001

**Exercício 001** - Faça um programa que exiba "Olá, Mundo!" na tela.

```pyhton
print('Olá, Mundo')
```

Este é um comando simples em python, geralmente o primeiro que aprendemos. Nesta linguagem, podemos tanto usar aspas simples quanto aspas duplas para escrever uma mensagem, não importando que tipo de caractere você coloque dentro. 

O `print()` ele se trata de um comando de saída que tem como objetivo mostrar algo na tela/terminal, a informação que será mostrada estará contida dentro de "()", podendo ser tanto um texto digitado diretamente, quanto uma variável.

---

### Ex002

**Exercício 002** - Faça um programa que leia o nome da pessoa e mostre uma mensagem de boas vindas.

```python
nome = input('Qual é o seu nome? ')

print('Olá, ', nome, '!! É um prazer em te conhecer!')
```
O objetivo deste exercício foi nos fazer aprender a colocar comandos dentro de uma variável, como o comando `input()`, afinal, em Python até uma variável é um objeto.

O comando `input()` é um comando de entrada, que serve para captar o que o usuário escreve, no caso do nosso código, estamos pegando o que o usuário escreve e armazenando dentro de uma variável.
