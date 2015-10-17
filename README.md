# examen
def calificacion ()
var numero=.11
var calificacion=0.0
for (i<-1 to 40)
{
println ("Ingresa tu calificacion")
calificacion=read float()
if (calificacion < numero)
{
menor=calificacion
}
}
println ("Calificacion menor"+menor)

def reloj ()
for (horas <- 0 to 23)
{
for (minutos <- 0 to 59)
{
for (segundos <- 0 to 59)
{
println (horas+"i"+min+"i"+segun)
}
}
}

def descuento ()
var kilos=0.0
val totalcliente=0.0
val totaltienda=0.0
println ("¿cuanto cuesta el kilo de naranja"?)
val preciokilo=readfloat()
for (i<1 to 15)
{
println ("¿cuantos kilos de naranja compraste?")
kilos=readfloat()
totalcliente=preciokilo*kilos
if (kilos > 10)
{
totalcliente=totalcliente*0.85
}
totaltienda+=totalcliente
println ("vas a pagar:"+totalcliente)
}
println ("la tienda va a recibir"+totaltienda)

def numeros ()
var numero=0.0
var cantidadpos=0
var cantidadnega=0
var contidadneutros=0
for (i<- 1 to 20)
{
println "ingresa un numero")
numero=readfloat()
if (numero>0)
{
cantidadpos+=1
}
else if (numero<0)
{
cantidadnega+=1
}
else
{
cantidadneutros+=1
}
}
println ("ingresaste"+cantidadpos+"numeros positivos")
println ("ingresaste"+cantidadnega+"numeros negativos")
println ("ingresaste"+contidadneutros+"numeros neutros")

println ("¿cual ejercicio quieres?")
println ("1)calificacion")
println ("2)reloj")
println ("3)descuento")
println ("4)numeros")
val opcion=readInt()
opcion match
{
case 1=>calificacion()
case 2=>reloj()
case 3=>descuento()
case 4=>numeros()
case default=>println ("opcion invalida")
}

