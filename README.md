
fun numerisDesc(n = int) {
  if(n = <=0) 
  {
    return
  }
  print(n)
  numerosDesc(n - 1)
}
fun main()
{
  val num = 5
  numerosDesc(num)
}
