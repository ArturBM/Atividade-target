Estágio Ribeirão Preto - 2024

1) 91, k vai aumentar de um em um até 13 e a variavel soma vai incorporar cada um desses valores em cada loop.

2) 
```
#include<stdio.h>
main()
{
	int fibonacci, num1, num2, numimput ;
	
	
	printf("Me informe um numero: ");
	scanf("%i", &numimput);
	
	
	num1= 0;
	num2= 1;
	
	
	while (numimput > fibonacci)
	{
		fibonacci = num1 + num2;
		num1 = num2;
		num2 = fibonacci;
	}
	
	if (numimput == fibonacci)
	{
		
		printf("%i pertence a sequencia de fibonacci.\n", numimput);
		
	}
	else
	{
		printf("%i nao pertence a sequencia de fibonacci.\n",numimput);
	}	
}
```
3a) 9;
3b) 128;
3c) 49;
3d) 100;
3e) 13;
3f) 200;

4) Ligue o interruptor 1 por 10 minutos, desligue e ligue o interruptor 2. Verifique um dos quartos, se tiver luz acesa é do interruptor 2, se a luz estiver apagada e estiver quente é o interruptor 1, e se estiver frio é o interruptor 3. Acenda qualquer outro interruptor e verifique as salas, a sala que estiver com luz ligada sera a sala que usara esse interruptor e a outra foi a que sobrou.

5) ```
   #include<stdio.h>
	#include<string.h>
	main()
	{
	//Escreva um programa que inverta os caracteres de um string.
	char inverter[30], imput[30];
	
	printf("Me informe uma palavra que vou inverte-la: ");
	scanf("%s", &imput);
	
	for (int i = 0; i < strlen(imput); i++ )
	{
		inverter[i] = imput[strlen(imput) - i - 1];	
	}
	
	printf("Sua string ao contrario fica: %s", inverter);
	

	}
```
