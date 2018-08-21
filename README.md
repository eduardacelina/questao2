import java.util.Scanner;
public class Intervalo {
    public static void main(String[] args) {
        Scanner tcl = new Scanner(System.in);
        System.out.print("Digite o numero de inicio");
        int inicio = tcl.nextInt();
        System.out.println("Digite o numero do fim");
        int fim = tcl.nextInt();
        for(int i = inicio + 1; i < fim; i ++){
            System.out.println(i);
        }
    }
    
}
