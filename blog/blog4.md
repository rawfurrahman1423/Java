# Post 4:

I went through this week learning more and practicing Java. I went deeper into the 
language and learned several new concepts. Although I was already familiar with 
some of the concepts from previous languages I have learned, I have become more 
fluent with them. The main concepts that I have become more familiar with are 
conditionals and the Switch statement. 

# New Concepts

## Conditionals

```Java
public class IfElseIf {
	public static void main(String[] args) {

		int round = 11;

		if (round > 12) {

			System.out.println("The match is over!");

		} else if (round > 0) {

			System.out.println("The match is underway!");

		}	else {

			System.out.println("The boxing match hasn't started yet.");

		}	
	}
}
```

The code above will print out “The match is underway!” This is because we have first 
created a variable with a value of 11. The code will be followed from top to bottom 
so the variable will be created and then the if/else will run. If the variable is 
greater than 12 (which it is not), then “The match is over will be printed. However 
if it is not true AND if the variable is greater than 0, then “The match is underway!” 
will be printed. If nothing is true, then “The boxing match hasn’t started yet.” 
will be printed. However there is more than one way to run a conditional. You can 
also use one line like the code below: 

```Java
//if else statement in a single line
public class Ternary {
	public static void main(String[] args) {
		
		int fuelLevel = 3;

		char canDrive = (fuelLevel > 0) ? 'Y' : 'N';
		System.out.println(canDrive);

	}
}
```

## Switch Statements

```Java
//using switch - will print out default
public class Switch {
	public static void main(String[] args) {
		
		char penaltyKick = 'X';

		switch (penaltyKick) {

			case 'L': System.out.println("Messi shoots to the left and scores!");
								break; 
			case 'R': System.out.println("Messi shoots to the right and misses the goal!");
								break;
			case 'C': System.out.println("Messi shoots down the center, but the keeper blocks it!");
								break;
			default:
				System.out.println("Messi is in position...");

		}

	}
}
}
```

The Switch statement runs in a similar way because it is also a conditional. The 
difference is that the code above will print out the default because the peneltyKick 
Char is set to ‘X’. The cases are ‘L’, ‘R’, and ‘C’. So the Default option will be ran. 


# Takeaways
+ Different coding languages have a lot in common
+ Java and Ruby are very similar because they are both languages based on class orientation 
+ There are multiple ways to do the same thing


[Next](blog5.md)

[Previous](blog3.md)

[Home](../README.md)