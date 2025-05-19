# Repositório de Correção da Lista de Exercícios Arrays 
## Exercícios

### Nível Básico

**1. Verificador de Idade (10 pontos)**

Crie um programa que receba um array com as idades de 5 pessoas: `[17, 21, 16, 25, 19]`

- Verifique quantas pessoas são maiores de idade (idade >= 18)
- Verifique quantas pessoas são menores de idade (idade < 18)
- Exiba as duas contagens no console

**2. Verificador de Números (10 pontos)**

Dado o array de números: `[12, 5, 8, 21, 16, 7, 30, 45, 13, 27]`

- Conte quantos números são pares
- Conte quantos números são ímpares
- Conte quantos números são maiores que 20
- Exiba os resultados no console

**3. Média de Notas (10 pontos)**

Crie um programa que calcule a média de notas de uma turma:

- Use o array: `[8.5, 7.0, 9.5, 6.5, 8.0, 7.5, 5.5, 6.0, 9.0, 10.0]`
- Calcule e exiba a média da turma
- Mostre quantos alunos tiraram nota acima da média
- Mostre qual foi a maior e a menor nota

### Nível Intermediário

**4. Transformador de Temperaturas (15 pontos)**

Crie um programa que converta uma lista de temperaturas de Celsius para Fahrenheit:

- Use o array: `[0, 10, 20, 30, 40]` (temperaturas em Celsius)
- Crie um novo array com as temperaturas convertidas para Fahrenheit usando a fórmula: F = C * 9/5 + 32
- Exiba ambos os arrays usando console.table()

**5. Calculadora de Desconto (15 pontos)**

Uma loja está com uma promoção onde produtos com preço acima de 100 reais têm 10% de desconto:

- Use o array de preços: `[150, 50, 220, 80, 120, 30, 480, 70, 90, 190]`
- Crie um novo array onde cada preço já esteja com o desconto aplicado (se necessário)
- Calcule quanto a loja vai perder com os descontos
- Calcule o valor médio dos produtos após os descontos

### Nível Avançado

**6. Organizador de Produtos (20 pontos)**

Uma loja precisa organizar seu estoque. Considere os seguintes arrays:

- Produtos: `["Teclado", "Mouse", "Monitor", "Gabinete", "Headset", "Mousepad"]`
- Preços: `[120, 80, 450, 350, 200, 35]`
- Quantidades: `[15, 25, 8, 5, 10, 30]`

Cada posição dos arrays corresponde a um produto (ex: Teclado custa 120 e tem 15 unidades).

Crie um programa que:

- Identifique qual é o produto mais caro e o mais barato
- Calcule o valor total do estoque (quantidade * preço de cada produto)
- Crie uma promoção onde os produtos com menos de 10 unidades em estoque têm 15% de desconto
- Exiba uma tabela com Nome, Preço Original, Preço com Desconto (se aplicável) e Quantidade

**7. Calculadora de Médias Ponderadas (20 pontos)**

Um professor precisa calcular as médias finais dos alunos. Considere:

- Nomes: `["João", "Maria", "Pedro", "Ana", "Carlos"]`
- Notas da Prova 1: `[7.5, 8.0, 6.5, 9.0, 7.0]` (peso 2)
- Notas da Prova 2: `[8.0, 7.5, 8.5, 8.0, 8.5]` (peso 3)
- Notas do Trabalho: `[6.0, 9.0, 7.0, 9.5, 6.5]` (peso 1)

Crie um programa que:

- Calcule a média ponderada de cada aluno (use a fórmula: (P1*2 + P2*3 + T*1) / 6)
- Identifique quais alunos foram aprovados (média >= 7.0)
- Identifique qual aluno teve a maior média final
- Crie e exiba uma tabela com Nome, Média e Situação (Aprovado/Reprovado)

## Bônus (exercícios opcionais)

**8. Simulador de Fila de Banco (20 pontos extras)**

Simule uma fila de banco onde pessoas podem entrar e sair da fila:

- Comece com o array: `["André", "Beatriz", "Carlos", "Daniel", "Eduardo"]`
- Simule as seguintes operações:
    1. "Fernanda" entra na fila
    2. As duas primeiras pessoas são atendidas (saem da fila)
    3. "Gabriel" e "Helena" entram na fila
    4. Mais uma pessoa é atendida
- Exiba a fila inicial e a fila final
- Exiba quantas pessoas foram atendidas e quantas pessoas ainda estão na fila