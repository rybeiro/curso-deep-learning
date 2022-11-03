# Fundamentos básico de Python
### Declarando variáveis, imprimir e identificar o tipo
```python
# Variáveis
a = 1
b = 2.2
c = 'Isso é uma string'
d = True

# Imprimindo
print(a)
print(b)
print(c)
print(d)

# exibir que tipo de dado
print(type(a))
print(type(b))
print(type(c))
print(type(d))
```

### Entrada de dados
```python
nome = input('Qual o seu nome: ' )
print('Seja bem vindo, ', nome)
```

## Operadores lógicos
```python
and
or
not
```

## Operadores comparação
```python
+ # soma
- # subtração
* # multiplicação
/ # divisão
% # módulo
```

## Estrutura de decisão
```python
nota = 7
if nota >= 7:
  print("aprovado")
elif nota > 5 and nota < 7:
  print("Recuperação")
else:
  print("Reprovado")
```

## Listas ( Vetor )
```python
vetor = [1,2,3]
vet = list(range(0,10))
```

## Estrutura de repetição ( Loop )
```python
# while
count = 1
while count < 5:
  print(count)
  count += 1

# for
for n in range(0,5):
  print(n)
```
## Módulos e pacotes
```python
# modulo - import 
import statistic
x = statistic.mean()

# modulo - função especifica
from statistics import mean
x = mean()

# modulo - usando alias
import statistic as est
x = est.mean()

# modulo - importar tudo
from statistic import *
mean()
median()
```
## Funções
```python
def saudacao:
 print("Seja bem vindo")

def saudacao(nome):
  print("Seja bem vindo, ", nome)

def saudacao(nome = "anonimo"):
  print("Seja bem vindo, ", nome)
``` 
