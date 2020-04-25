#include <iostream>



int main(int argc, char** argv) 
{
	int opcao;
	int valor;
	
	printf ("conversor bases \n");
	printf ("1: decimal para hexadecimal \n");
	printf ("2: hexadecimal para decimal \n");
	printf ("informe a opcao: ");
	scanf ("%d", &opcao);
	getchar();
	
	if(opcao ==1)
	{
		printf ("\ninformar o valor em decimal:");
		scanf ("%d",&valor);
		getchar ();
		printf ("%d em hexadecimal eh: %x \n",valor, valor);
		
		
	
	}
	else if (opcao==2)
	{
		printf ("informar o em hexadecimal:");
		scanf ("%x", &valor);
		getchar();
		printf("%x em decimal eh: %d \n", valor, valor);
		
	}
	else printf ("\nsua opcao eh invalida.");
	
	system ("PAUSE");

	return 0;
}
