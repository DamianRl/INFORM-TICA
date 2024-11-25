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
   Gestión de símbolos 








## ANÁLISIS DE DISCURSO
    universo.nombre = (“Restaurante”)
    universo.discurso.comienzo
        El Universo es un restaurante. De los clientes se conocen los datos habituales, también de los platillos, de los cocineros y de las ventas.
    universo.discurso.fin


    -cliente
    -platillo
    -cocinero
    -venta
    -restaurante
    -_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_
    v2
    universo.discurso.comienzo
	    restaurante de platillos
	    -cliente: se conocen los datos habituales
	    -platillo:se conocen los datos habituales
	    -cocinero:.se conocen los datos habituales
	    -venta: se conocen los datos habituales
    universo.discurso.fin

    -_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_
    v3(con diseño)
	    -restaurante(de platillos)
	    -cliente(DNI, nombre, apellido, teléfono, dirección,...)
	    -Platillo(numPlatillo, ingredientesPrinc,precio, cantidadPorPersona,...)
	    -cocinero(numCocinero, dni, nombre, ape, tf,...)
	    -venta(platillo, cliente,cocinero, importe, fecha…)


