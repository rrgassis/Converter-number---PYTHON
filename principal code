num = int(input('Digite um número decimal:\n'))
num_digitado = num
result= 1
lista = []


while result >= 1:
   resto = num % 2
   lista.insert(0, resto)
   result = num // 2
   num = result


binario = ''.join([str(item) for item in lista])
print(f'O número decimal', num_digitado, 'convertido em binário é:', binario)
