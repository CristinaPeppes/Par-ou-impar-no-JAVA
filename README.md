# Par-ou-impar-no-JAVA
Programa JAVA para dizer se um número é par ou impar

package questao1;

import java.util.Scanner;

public class Questao1 {

    public static void main(String[] args) {
        
        Scanner ler = new Scanner(System.in);
        
        int numero;
        
        System.out.print("Digite um número: ");
        numero = ler.nextInt();
        
        if(numero % 2 == 0){
        System.out.println("O número é par");
        }
        else{
        System.out.println("O número é impar");
        }
    }
    
}
