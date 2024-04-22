
import java.util.Scanner;

public class app {
    
    public static void main (String[] args){
        
        Scanner teclado = new Scanner(System.in);
        
        System.out.println (" Escreva o seu nome: ");
        
        String nome = teclado.nextLine();
        
        System.out.println (" Escreva o seu sobrenome: ");
        
        String sobrenome = teclado.nextLine();
        
        String nomecompleto = (nome.trim() + " " +sobrenome.trim() );
        
        nomecompleto = nomecompleto.toUpperCase();
        
        int tamanho = nomecompleto.length();
        
        char primeiraletra = nomecompleto.charAt(0);
        
        System.out.printf (" seu nome completo é %s.\n", nomecompleto );
        
        System.out.printf (" Ele tem %d caracteres.\n", tamanho );
        
        System.out.printf (" A primeira letra é %c.\n", primeiraletra );
        
    }
    
}
  
