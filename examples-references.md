```Java
//Print my name
public class YourName {
	public static void main(String[] args) {

		System.out.println("rawfur");

	}
}
```


```Java
//Integer
public class DataTypes {
	public static void main(String[] args) {

		System.out.println(5);

	}
}
```


```Java
//boolean (true or false)
public class DataTypesB {
	public static void main(String[] args) {

		System.out.println(false);
		System.out.println(true);
	}
}
```


```Java
//Char (character) - must have only have 1 parenthesis 
public class DataTypesC {
	public static void main(String[] args) {

		System.out.println('B');

	}
}
```


```Java
//Setting values for integer, boolean, and char variables
public class Variables {
	public static void main(String[] args) {

		int myNumber = 42;
		boolean isFun = true; 
		char movieRating = 'A'; 

	}
}
```


```Java
//conditionals (if else)
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


```Java
class Car {

    int modelYear;

    public Car(int year) {

        modelYear = year;

    }

    public void startEngine() {
        System.out.println("Vroom!");
    }

    public void drive(int distanceInMiles) {

        System.out.println("Miles driven: " + distanceInMiles);

    }

    public static void main(String[] args){

        Car myFastCar = new Car(2007);
        myFastCar.startEngine();
        myFastCar.drive(1628);

    }
```

