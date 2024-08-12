# Recursividad

~~~

fun numerosDesc(n: Int) {
  if(n <= 0) 
  {
    return
  }
  println(n)
  numerosDesc(n - 1)
}
fun main()
{
  val num = 5
  numerosDesc(num)
}

~~~

Es una funcion que se llama a si misma para resolver un problema.

### Componentes 

###### Caso base: 

~~~
 if(n = <=0) 
  {
    return
  }
~~~

La condicion que termina la recursion y evita un ciclo infinito.

###### Llamada Recursiva:

~~~
numerosDesc(n - 1)
~~~

la funcion se llama a si misma con argumentos que progresan hacia el caso base. 
