# abecedario

def letras_generador():
    yield "contador de letras"
    conteo = 'A'
    while conteo <= 'M':
        yield conteo
        conteo = chr(ord(conteo)+1)
for letras in letras_generador():
    print(letras)
