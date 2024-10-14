# INFORMÁTICA
Notas para informática
## FOTO
[TOMATE](https://drive.google.com/file/d/1Jyy32F9d8CczdvKsBTJT6T-zo9TAfxd-/view)
## TABLA
|A|B|
|:-:|:-|
|aa|bbbbb|
## CLI-SVR
OK= True

def svr(dato, control=OK):

    print(f"svr: recibido: {dato}")
    
    return OK

def cli():

    print("cli: begin")
    
    svr(22)
    
    print("cli: end")

main ------------------------------

cli()
## CLI-SVR V2

INCREMENTA = 1

DUPLICA = 2

def operacion(dato, op = INCREMENTA):

    print(f"svr: recibido: {dato} y {op}")
    
    if op == INCREMENTA:
    
        return dato + 1
        
    if op == DUPLICA:
    
        return dato * 2
    
def cli():

    print("cli: begin")
    
    retorno = operacion(22, INCREMENTA)
    
    print(f" cli: recibido: {retorno}")
    
    retorno = operacion(33, DUPLICA)
    
    print(f" cli: recibido: {retorno}")
    
    print("cli: end")
    

main ------------------------------

cli()

## APUNTES
