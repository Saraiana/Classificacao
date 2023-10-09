# Exercicio-34
Classificação por faixa etária
Elaborar um algorítmo que, dada a idade de um nadador. Classifique-o em uma das seguintes categorias:

a. Infantil A = 5 - 7 anos;

b. Infantil B = 8 - 10 anos;

c. Juvenil A = 11- 13 anos;

d. Juvenil B = 14 - 17 anos;

e. Sênior = 18 - 25 anos.

Apresentar mensagem “idade fora da faixa etária” quando for outro ano não contemplado;

# Código
package Exercicio34;

import java.util.*;

public class Main {

    public static void main(String[] args) {
        
        Scanner leitor = new Scanner(System.in);
        
        int idade;
        
        System.out.println("Informe a idade do nadador");
        idade = leitor.nextInt();
        
        if (idade >= 5 && idade <= 7) {
            System.out.println("O nadador pertence a categoria infantil A.");
        } else {
        if (idade >= 8 && idade <= 10) {
            System.out.println("O nadador pertence a categoria infantil B.");
        } else {
        if (idade >= 11 && idade <= 13) {
            System.out.println("O nadador pertence a categoria juvenil A.");
        } else {
        if (idade >= 14 && idade <= 17) {
            System.out.println("O nadador pertence a categoria juvenil B.");
        } else {
        if (idade >= 18 && idade <= 25) {
            System.out.println("O nadador pertence a categoria sênior.");
        } else {
            System.out.println("Idade fora da faixa etária.");
        }
        }
        }
        }
        }
        
    }
    
}
