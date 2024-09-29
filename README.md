## Descrição do Programa

Este programa em Python inverte os caracteres de uma string sem usar funções prontas. A função `inverter_string` percorre a string de trás para frente, adicionando cada caractere a `resultado`. O exemplo inverte "Exemplo de string" para "gnirts ed olpmxE". Fácil de entender e útil para iniciantes!

### Código

```python
def inverter_string(s):
    # Inicializa uma string vazia para armazenar o resultado
    resultado = ""
    # Percorre a string original de trás para frente
    for i in range(len(s) - 1, -1, -1):
        resultado += s[i]
    return resultado

# String de exemplo
string_original = "Exemplo de string"
string_invertida = inverter_string(string_original)

print("String original:", string_original)
print("String invertida:", string_invertida)
