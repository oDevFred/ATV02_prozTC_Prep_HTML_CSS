# Atividade 02 - Talento Cloud

Este projeto faz parte do curso **Talento Cloud**, oferecido pela **Proz** em parceria com a **AWS**. Atualmente, estou no módulo **Preparação para HTML/CSS**. Nesta atividade, vamos trabalhar com um array de músicos em Python e realizar algumas operações com ele. O código foi desenvolvido no **Google Colab** (Pode ser acessado aqui: https://colab.research.google.com/drive/10qk4dw1haHwiUH_XjXIKHxEp1qDFrim_?usp=sharing).

## Descrição da Atividade

Nesta atividade, o objetivo é copiar um array de músicos e imprimir no terminal:

1. A quantidade de elementos que ele possui.
2. O dado salvo no índice 2.
3. O dado salvo no índice 9.
4. O dado salvo no índice 14.

Isso ajudará a entender como manipular listas em Python, incluindo acesso a elementos por índices e utilização da função `len()` para contar elementos.

## Estrutura do Código

O código contém as seguintes etapas:

1. Declaração da lista `lista_musicos`.
2. Cálculo da quantidade de elementos com a função `len()`.
3. Acesso aos elementos nos índices 2, 9 e 14.
4. Impressão dos resultados no terminal com o uso da função `print()`.

## Código

```python
# Declaração da lista de músicos
lista_musicos = [ 'Djavan', 'Roberto Carlos', 'Elis Regina', 'Tom Jobim', 'Milton Nascimento', 
                  'Chico Buarque', 'Nara Leão', 'Pitty', 'Simonal', 'Moacir Santos', 
                  'Caetano Veloso', 'Elza Soares', 'Paulinho da Viola', 'Yamandú Costa', 'Gal Costa']

# Cálculo da quantidade de elementos na lista
qtd_elementos = len(lista_musicos)

# Acesso aos elementos nos índices 2, 9 e 14
index2 = lista_musicos[2]
index9 = lista_musicos[9]
index14 = lista_musicos[14]

# Impressão dos resultados no terminal
print(qtd_elementos)
print(index2)
print(index9)
print(index14)
```

## Resultado Esperado

Ao rodar este código, o terminal deverá exibir:

```
15  # quantidade de elementos
Elis Regina  # dado no índice 2
Moacir Santos  # dado no índice 9
Gal Costa  # dado no índice 14
```

## Tecnologias Utilizadas

- **Python**: Linguagem de programação usada para realizar a atividade.
- **Google Colab**: Ambiente de desenvolvimento onde o código foi executado.

## Sobre o Projeto Talento Cloud

Este projeto faz parte da formação em programação promovida pela Proz em parceria com a AWS, através do programa Talento Cloud, que visa capacitar alunos com competências em programação e desenvolvimento de software.
