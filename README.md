package program;
import java.util.*;
public class voto {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc = new Scanner(System.in);
		int joao=0;
		int maria=0;
		int nulo=0;
		int branco=0;
		int voto=0;
		System.out.println("informe o voto");
		voto= sc.nextInt();
		while (voto !=0) {
			if(voto==1) {
				joao = joao+1;
			}
			else if(voto ==2) {
				maria =maria+1;
				
			}

			else if (voto==3) {
				nulo =nulo+1;
				
			}
			else if (branco==4) {
				branco = branco +1;
			}

		System.out.println("informe o voto");
		 voto = sc.nextInt();
		}

		System.out.println("final dos votos");	
		System.out.println("votos de joao silva" + joao);	
		System.out.println("votos de maria dos santos "+ maria);	
		System.out.println("votos nulos "+nulo);	
			System.out.println("votos em branco " + branco);
			
			}

		
	}


