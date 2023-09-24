# Zachary Reece
## CPE-322 - Engineering Design VI

![image](https://github.com/DZiggle/CPE-322/assets/144705148/5f445d9b-2e2d-48ed-872a-796d655980c4)
> “The more you know, the more you realize you know nothing.” - Socrates

Here's a list of coding languages I have learned:
- Java
(I'm most familiar with Java)
- Python
(I'm excited to learn more this semester)
- C
(I want to get into C++ as well)
- Assembly Language :cry:
(This was brutal and I'm glad it's over) 

The C program I am most proud of coding is a football player database that allows you to search and update player information and statistics. :football:
> [!WARNING]
> I coded this back in community college and I have not coded in a while, so I am a bit rusty now.
Either way, here is a sample of that code:
```
main(){
	int entry, i;					
	int saved = 0;						
	char nameEntry[30];   		
	
	// Struct for football player's information
	struct footballPlayer Player[10];			
		strcpy(Player[0].name, "Player1");  strcpy(Player[0].position, "position");
		strcpy(Player[1].name, "Player2");  strcpy(Player[1].position, "position");
		strcpy(Player[2].name, "Player3");  strcpy(Player[2].position, "position");
		strcpy(Player[3].name, "Player4");  strcpy(Player[3].position, "position");
		strcpy(Player[4].name, "Player5");  strcpy(Player[4].position, "position");
		strcpy(Player[5].name, "Player6");  strcpy(Player[5].position, "position");
		strcpy(Player[6].name, "Player7");  strcpy(Player[6].position, "position");
		strcpy(Player[7].name, "Player8");  strcpy(Player[7].position, "position");
		strcpy(Player[8].name, "Player9");  strcpy(Player[8].position, "position");
		strcpy(Player[9].name, "Player10"); strcpy(Player[9].position, "position");
		

	//Proccess - sets 0s as defaults for # of touchdowns, catches, passing/receiving/rushing yards
	for(i=0; i <10; i++){
		Player[i].touchdowns = 0;
		Player[i].catches = 0;
		Player[i].passingYards = 0;
		Player[i].receivingYards = 0;
		Player[i].rushingYards = 0;
	}
```

Here are my results from the half adder vhdl:
![image](https://github.com/DZiggle/CPE-322/assets/144705148/480b364d-a6af-48a4-bdd4-45f3c680462d)
