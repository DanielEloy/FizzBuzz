# FizzBuzz
 Programa que imprime os números de 1 a 100. Mas para múltiplos de * três imprimem "Fizz" em vez do número e para os múltiplos de cinco * imprima "Buzz". Para números que são múltiplos de três e cinco * imprima "FizzBuzz".
/**
* @autor Daniel Eloy
* 
* Programa que imprime os números de 1 a 100. Mas para múltiplos de
* três imprimem "Fizz" em vez do número e para os múltiplos de cinco
* imprima "Buzz". Para números que são múltiplos de três e cinco
* imprima "FizzBuzz".
**/

package FizzBuzz;
class  FizzBuzz {
	public static void main(String[] args) {
        for ( int x =  1 ; x <=  100 ; x ++ ) {
            if ((x %  3  ==  0 ) && (x %  5  ==  0 )) {
                System.out.println ( " FizzBuzz " );
            } else  if (x %  3  ==  0 ) {
                System.out.println ( " Fizz " );
            } else  if (x %  5  ==  0 ) {
                System.out.println ( " Buzz " );
            } else {
                System.out.println (x);
            }
        }
    }
}
