# LG2Array

Aluna Giulia Santana dos Anjos SP3025918 
Arquivo do word com os exercicios em FILES.

Exercicios sobre Array

1.	Seja um array de inteiros de nove elementos. Escreva um programa em java que realize a seguinte sequência de ações, na ordem indicada:
a)	Preencha o array com o valor do índice de cada elemento;
b)	Imprima os elementos do array;
c)	Mulfiplicar cada elemento do array por 3;
d)	Repefir o item b;


package LG2Array;

public class Exe1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
				
			int[] indice = new int[9];
					
			for(int i=0; i <= 8; i++) {
			indice[i] = i;
			System.out.println("os valores são:" + indice[i]);
			
			}
			
			for(int i=0; i <= 8; i++) {
				indice[i] = indice[i]*3;
				System.out.println("os valores multiplicados por 3, são:" + indice[i]);
		}
	}
}


2.	Faça um programa em java que preencha um array de 10 elementos com valores do índice em ordem inversa, ou seja, preenchendo da úlfima posição até a primeira.


package LG2Array;

public class Exe2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int[] x = new int[10];
		
		for(int i=9; i >= 0; i--) {
		x[i] = i;
		System.out.println("o " + i + "º valor do vetor é:" + x[i]);
		}

	}
	
}


3.	Seja um array bidimensional de inteiros de 100 x 100. Escreva um programa em java que realize a seguinte sequência de ações, na ordem indicada:
a)	Preencha o array bidimensional com o valor da subtração dos índices de cada elemento;
b)	Imprima os elementos do array bidimensional;
c)	Mulfiplicar os índices de cada elemento por 7;
d)	Repetir o item b;


package LG2Array;

public class Exe3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		int[][] x = new int[100][100];
		
		for(int i=0; i <= 99; i++) {
			for(int j=0; j <= 99; j++) {
				x[i][j] =i-j;
				System.out.println(x[i][j]);
			}
		}
		for(int i=0; i <= 99; i++) {
			for(int j=0; j <= 99; j++) {
				x[i][j] = x[i][j]*7;
				System.out.println(x[i][j]);
			
			}
		
		}
	}

}



4.	Faça um programa em java que preencha um array bidimensional de 50 x 100 posições com valores da soma dos índices em ordem inversa, ou seja, preenchendo da úlfima linha até a primeira.

package LG2Array;

public class Exe4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int[][] x = new int[50][100];
		
		for(int i=49; i >= 0; i--) {
			for(int j=99; j >= 0; j--) {
				x[i][j] =i + j;
				System.out.println(x[i][j]);
			}
	
		}
	}
}
