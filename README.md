# exercicios
exerciciosJava
package win;

import java.util.Scanner;

public class dowhile {

	public static void main(String[] args) {

		Scanner can = new Scanner (System.in);
		
		/*System.out.println("Sem scanner.");
		System.out.println("");
		System.out.println("Estruturas de controle.");
		System.out.println("Uso do 'if'");
        System.out.println("");	    
           
        char sex = 'M';
        
        System.out.println("Sexo = M - Masculino.");
        
        if (sex == 'M') {
        	System.out.println("Alistamento militar obrigatório.");
        }
        
        System.out.println("");
        
        System.out.println("Com scanner.");
        System.out.println("");
        System.out.println("Entre com o sexo: M/F");
        String sexo = can.next();
        
        if (sexo.equalsIgnoreCase("m")) {
        	System.out.println("Alistamento militar obrigatório.");
        } else if (sexo.equalsIgnoreCase("f")) {
        	System.out.println("Alistamento militar opcional.");
        } else { 
        	System.out.println("Entre com o sexo correto. M/F");
        }*/
     
		//____________________________________________________________________
		
        /*System.out.println("Uso do 'For'");
        
        System.out.println("");
        
        for (int i = 10; i > 0; i--) {
        	System.out.println("hello");
        }*/
		
        //______________________________________________________________________ 
      
		//minhas 10 linhas em quatro linhas de código
		
		/*System.out.println("Tabuada.");
         for (int a = 10; a > 0; a--) {
        	for (int b = 10; b > 0; b--)
        	System.out.println("1 x " + b + " = ");
        	break;
        }*/
        
        //as 10 linhas de código do professor em três linhas de código
        
        /*for (int tabuada = 1; tabuada <= 10; tabuada++) {
        	System.out.println("");
        	for (int valor = 1; valor <= 10; valor ++) {
        		System.out.println(tabuada + " x " + valor + " = " + (tabuada * valor));
        	}
        }*/
		
		//_________________________________________________________________________
		
		
		System.out.println("Uso da estrutura ");
		
		
		int contador = 1;
		while (contador <= 10) {
			System.out.println(contador);
		}
		
	}

}
