//fatorial';

void main() {
  //var rand = Random();
 
  
// List<int> lista = [List.generate(10, (_) => 
 //               rand.nextInt(11))];
   List<int> lista = [1,2,3,4,5,6,7,8,9];
  
  
  lista.forEach((numero) => 
             print('Nº($numero) = ${teste(numero)}')
          );
  
//   for(var numero in lista)
//     print('teste($numero) = ${teste(numero)}');
}

// f(n) -> f(n - 1) * 2 para n > 2
// f(n) -> n * f(n - 1)
int teste(int n) {
  if(n <=0) return 1;
  return n * teste(n-1);
  
  //return n > 2 ? teste(n - 1) * 2 : 1;
}

