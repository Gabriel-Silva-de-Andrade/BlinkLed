# BlinkLed
Biblioteca controle de tempo do Piscar de LEDs (arduino)


#include "BlinkLed.h"

#define Led_Vm 8 

#define Led_Az 7 


BlinkLed Led_Vermelho(Led_Vm);

BlinkLed Led_Azul(Led_Az);


void setup() {
 
}

void loop() {
    
    Led_Vermelho.ONoff_Light (50, 500);   // ( HIGH, LOW )
    Led_Azul.ONoff_Light (1000, 1000);     // ( HIGH, LOW )
       
}
