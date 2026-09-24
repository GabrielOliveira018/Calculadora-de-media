## Calculadora-de-media ##
# calcula media de duas notas de um aluno e imprimi o resultado. #

# python versao: 3.14

# copie o codigo vá algum app que de para programar em python e cole e execute.

# eu mesmo que fiz.

def calcular_media( nota1, nota2 ):
    return ( nota1 + nota2 )/ 2

print('=== Sistema de notas do aluno ===')
n1 = float(input("Digite a primeira nota:"))
n2 = float(input("Digite a segunda nota:"))
media = calcular_media(n1, n2)
print (f"A média final é: {media:.2f}")

if media >= 7.0:
    print("APROVADO")
else:
    print("REPROVADO")


