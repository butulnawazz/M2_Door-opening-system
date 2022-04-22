
//![TestCases](https://user-images.githubusercontent.com/102668684/164627176-3758bf23-9df1-4b68-827a-b4e896beb5c6.png)

Door sensor is connected to B1 when the system is on the logic high
and door is open

DDRB=DDRB&0b11111101;  //fd

//led is connected to voltage source and led starts blinking
	DDRC=DDRC|0b01000000;  //40
  
	
 if port B1 logic goes low
 
if(PINB & 0b00000010) //02


//led stops blinking

	PORTC=PORTC|0b01000000;//40
  
		else
 //  led continues to blink 
   
		PORTC=PORTC&0b10111111;//bf
    
    
