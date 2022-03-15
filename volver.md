# Previa del Fork

void continuar_juego(int UserOption) {//para continuar jugando
  printf("Si quieres volver a jugar presiona 1, en caso de que quieras salir presiona 4 \n");
	scanf ("%d", &UserOption);
   if (UserOption==4) {printf("ADIÓS :D ");
     exit(0);}
  
  

	
}



int main(void){
	int UserOption;
  ask_option(&UserOption); 
  
while (UserOption!=4){
  	verificaGanador(UserOption);
    continuar_juego(UserOption);
    ask_option(&UserOption); 
  }
  system("pause()");
  ask_option(&UserOption); 
  
  }
