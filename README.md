# geraMpackage geraNumMegSen;

import java.util.Random;

public class Randon {
	
	

	public static void main(String[] args) {
		
		Random random = new Random();
		

		
		int numeroInteiro_0_a_60 = random.nextInt(10);
		System.out.println(" 1 aposta:  " + numeroInteiro_0_a_60);
		
		int numeroInteiro_10_a_60 = random.nextInt(20);
		System.out.println(" 2 aposta:  " + numeroInteiro_10_a_60);
		
		int numeroInteiro_20_a_60 = random.nextInt(30);
		System.out.println(" 3 aposta:  " + numeroInteiro_20_a_60);
		
		int numeroInteiro_30_a_60 = random.nextInt(40);
		System.out.println(" 4 aposta:  " + numeroInteiro_30_a_60);
		
		int numeroInteiro_40_a_60 = random.nextInt(50);
		System.out.println(" 5 aposta:  " + numeroInteiro_40_a_60);
		
		int numeroInteiro_50_a_60 = random.nextInt(60);
		System.out.println(" 6 aposta:  " + numeroInteiro_50_a_60);
		
	}
		
		
}
