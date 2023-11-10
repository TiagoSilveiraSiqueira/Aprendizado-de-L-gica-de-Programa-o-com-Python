## 1. Introdução à Lógica de Programação

### 1.1 O que é Lógica de Programação?

**Lógica de programação** é a habilidade de organizar pensamentos e instruções de maneira clara para resolver problemas computacionais. Em outras palavras, é a arte de criar algoritmos eficientes.

### 1.2 Por que é Importante?

- **Organização do Pensamento:** A lógica de programação ajuda a estruturar ideias de forma ordenada, facilitando a resolução de problemas complexos.
  
- **Eficiência:** Um programa bem escrito é mais eficiente, economizando recursos de computação.

- **Base para Linguagens Futuras:** A lógica adquirida pode ser aplicada a qualquer linguagem de programação, tornando a transição para outras linguagens mais suave.

### 1.3 Exemplo Prático

Vamos considerar um problema comum: **Calcular a Média de Notas de Alunos**.

#### Algoritmo:

1. **Receber as Notas:**
   - Solicitar ao usuário as notas dos alunos.

2. **Calcular a Média:**
   - Somar as notas e dividir pelo número de notas.

3. **Exibir o Resultado:**
   - Apresentar a média calculada.

#### Código em Python:

```python
# Passo 1: Receber as Notas
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))

# Passo 2: Calcular a Média
media = (nota1 + nota2) / 2

# Passo 3: Exibir o Resultado
print(f"A média das notas é: {media}")
