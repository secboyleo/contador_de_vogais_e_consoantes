# contador_de_vogais_e_consoantes

```
def conta_letras(frase, contar="vogais"):
    vogais = 'aeiouAEIOU'
    consoante = 'bcdfghjklmnpqrstvwxyzBCDFGHJKLMNPQRSTVWXYZ'
    cont_vogal = 0
    cont_consoante = 0
    
    for letra in frase:
        if letra in vogais:
            cont_vogal += 1
        elif letra in consoante:
            cont_consoante += 1
            
    if contar == 'consoantes':
        return cont_consoante
    else:
        return cont_vogal
```
