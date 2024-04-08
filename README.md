# Estudo Python com Orientação a Objetos

# Avaliação de Restaurantes

Este programa em Python é uma aplicação para avaliação de restaurantes, onde os usuários podem fornecer notas para os restaurantes cadastrados e visualizar as avaliações médias de cada restaurante.

## Funcionalidades

- **Cadastro de Restaurante:** Permite cadastrar um novo restaurante fornecendo seu nome e categoria.
- **Listagem de Restaurantes:** Lista todos os restaurantes cadastrados, exibindo seus nomes, categorias, avaliações médias e status de atividade.
- **Alternar Estado do Restaurante:** Altera o estado de atividade de um restaurante entre ativo e inativo.
- **Receber Avaliação:** Permite que os usuários enviem avaliações para os restaurantes, fornecendo o nome do cliente e a nota de 1 a 5.
- **Cálculo da Média das Avaliações:** Calcula a média das avaliações recebidas para cada restaurante.

## Como Usar

1. Execute o arquivo `avaliacao_restaurantes.py` em um ambiente Python.
2. Siga as instruções exibidas no console para cadastrar restaurantes, receber avaliações e visualizar os resultados.

## Requisitos

- Python 3.x

## Exemplo de Uso

```python
from modelos.restaurante import Restaurante

restaurante_praca = Restaurante('praça', 'Gourmet')
restaurante_praca.receber_avaliacao('Gui', 10)
restaurante_praca.receber_avaliacao('Lais', 8)
restaurante_praca.receber_avaliacao('Emy', 5)

Restaurante.listar_restaurantes()

## Autor
Projeto base de estudo do curso Python com Orientação a Objetos da Alura .
