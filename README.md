/* 
  file: area_triangolo.c
  autore: Gabriele Corona
  data: 26/9/22
  classe: 3H
  
  Calcola l'area di un triangolo
  
  Input: base, altezza
  Elaborazione: tutte le istruzioni per passare dall'input all'output
  Output: un numero con la virgola
*/
#include<stdio.h>//printf, scanf
int main()
{
	//dichiariamo le due variabili di input
	float base, altezza;
	//e output
	float area;
	
	//Input: base, altezza
	//avvalorare input
	printf("Inserisci il valore della base\t");
	scanf("%f", &base);
	printf("Inserisci il valore dell'altezza\t");
	scanf("%f", &altezza);
	
	//Elaborazione: tutte le istruzioni per passare dall'input all'output
	//assegna alla variabile area il risultato dell'espressione base * altezza
	area= base*altezza;
	
	//Output: un numero con la virgola
	//visualizza output
	printf("Area triangolo=\t %.2f",area);
	
	//terminiamo il programma
	return 0;
}
