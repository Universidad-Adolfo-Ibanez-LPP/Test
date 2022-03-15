# Previa del Fork
#include <stdio.h>
#include <stdlib.h> 
void verificaGanador(int UserOption) {
  int PcOption;
	PcOption= (rand()%3)+1; // genera un numero aleatorio del 1 al 3
	printf("La ópción de la máquina fue %i \n",PcOption);
	
	if(UserOption==PcOption) printf("\nEmpataste\n");
    if((UserOption==2)&&(PcOption==1)) printf("\nGanaste\n");
 	if((UserOption==1)&&(PcOption==2)) printf("\nPerdiste\n");
	if((UserOption==3)&&(PcOption==1)) printf("\nPerdiste\n");
	if((UserOption==3)&&(PcOption==2)) printf("\nGanaste\n");
	if((UserOption==2)&&(PcOption==3)) printf("\nPerdiste\n");
	if((UserOption==1)&&(PcOption==3)) printf("\nGanaste\n");
  
 

}
