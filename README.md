# Calculadora de Média do Aluno
## Título e Descrição
Este projeto é uma calculadora de média do aluno desenvolvida em Python.
## Tecnologias Utilizadas
- Python 3
- Visual Studio Code
## Como Instalar e Executar
1. Instale o Python 3.
2. Abra o projeto no Visual Studio Code.
3. Abra o arquivo `calculadora.py`.
4. Execute o programa pelo botão de execução do VS Code ou pelo terminal:
# Exemplo de Uso ou Demonstração
# Projeto Exemplar: Calculadora de média do aluno

```
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2
print("=== Sistemas de Notas do Aluno===")
n1 = float(input("Digite a primeira nota:"))
n2 = float(input("Digite a segunda nota"))
media = calcular_media(n1, n2)
print(f"A média final é: {media:.2f}")
if media >= 7.0:
        print("Status: APROVADO!")
else:
     print("Status: REPROVADO.")

Exemplo de saída:

=== Sistemas de Notas do Aluno===
Digite a primeira nota:6
Digite a segunda nota8
A média final é: 7.00
Status: APROVADO!

```
# Autor e Contato
isaquealves.santos@gmail.com<br>
www.linkedin.com/in/isaque-alves1