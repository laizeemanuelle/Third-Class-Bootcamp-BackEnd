using System;
					
public class Program
{
	public static void Main()
	{
		Console.WriteLine("***Calculando a média de notas de Alunos***");
		
		//variavel para a contagem de alunos com a média calculada
		int contadorDeAlunos = 0;
		
		//variavel que informa a quantidade de alunos que terão a média calculada
		
		int quantidadeDeAlunos = 5;
		
		while (contadorDeAlunos < quantidadeDeAlunos )
		{ 
			Console.Write ("Informe o numero de matricula: ");
			string matricula = Console.ReadLine();
			
			Console.Write ("Informe a Nota 01: ");
			decimal nota01 = Convert.ToDecimal(Console.ReadLine());
			
			Console.Write ("Informe a Nota 02: ");
			decimal nota02 = Convert.ToDecimal(Console.ReadLine());
			
			Console.Write ("Informe a Nota 03: ");
			decimal nota03 = Convert.ToDecimal(Console.ReadLine());
			
			Console.Write ("Informe a Nota 04: ");
			decimal nota04 = Convert.ToDecimal(Console.ReadLine());
			
			//Calcular a média dos Alunos
			decimal mediaAluno = (nota01 + nota02 + nota03 + nota04) / 4;
			
			//exibir se o aluno foi aprovado ou não 
			if(mediaAluno >= 7)
			{
				Console.WriteLine( "O aluno " + matricula + " foi aprovado com média " + mediaAluno);
			}
			else 
			{ 
				Console.WriteLine("O aluno " + matricula + " foi reprovado com média " + mediaAluno);
			}
			contadorDeAlunos++;
		}
	}

  }





	





			
			
			
		

