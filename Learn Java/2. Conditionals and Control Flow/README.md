
## 2. Boolean Operators: &&

    	public class And {
    		public static void main(String[] args) {
        	System.out.println(true && true);
    		}
	}
    
## 3. Boolean Operators: ||
	
	public class Or {
	   	public static void main(String[] args) {
		System.out.println(true || true);
		}
	}
    
   
## 4.  Boolean Operators: ! 

    public class Not {
	public static void main(String[] args) {

		System.out.println(!false);
		System.out.println( !(5>=1) );	
		}
	}
    
## 5. Boolean Operators: Precedence
  
    public class Precedence {
	public static void main(String[] args) {

		boolean riddle = !( 1 < 8 &&  (5 > 2 || 3 < 5));
		System.out.println(riddle);

		}
	}
    
## 6. If Statement

    public class If {
	public static void main(String[] args) {
		if (true) {
			System.out.println("Access granted.");
		}}
		}
    
## 7. If-Else Statement
 
     public class IfElse {
	public static void main(String[] args) {
		if (!(7 <= 7)) {
			System.out.println("Try again...");

		} else {
			System.out.println("Success!");
		}
	}
	}
    
## 8. If-ElseIf-Else Statement   

     public class IfElseIf {
	public static void main(String[] args) {
		int round = 1;
		if (round > 12) {
			System.out.println("The match is over!");
		} else if (round > 0) {
			System.out.println("The match is underway!");
		}	else {
			System.out.println("The boxing match hasn't started yet.");
		}	
	}
	}
    
## 9. Ternary Conditional
	
	public class Ternary {
		public static void main(String[] args) {
		int fuelLevel = 3;
		char canDrive = (fuelLevel > 0) ? 'Y' : 'N';
		System.out.println(canDrive);

	}
	}
    
## 10. Switch Statement

    public class Switch {
	public static void main(String[] args) {
		char penaltyKick = 'L';
		switch (penaltyKick) {
			case 'L': System.out.println("Messi shoots to the left and scores!");
					break;
			case 'R': System.out.println("Messi shoots to the right and misses the goal!");								break;
			case 'C': System.out.println("Messi shoots down the center, but the keeper blocks it!");
					break;
			default:
				System.out.println("Messi is in position...");

		}

	}
  	 }
    
## 11. Generalizations

    public class GeneralizationsB {
	public static void main(String[] args) {
	boolean tricky = false;
	if(2015 > 2016) {
			System.out.println("Stuck in the past...");
		}else {
			System.out.println("Upgraded to the future!");
		}
	int subwayTrain = 5;
		switch (subwayTrain){
			case 1 : System.out.println("This is a South Ferry bound train!");
					break;
			case 5 : System.out.println("This is a Brooklyn bound train!");										break;
			case 7 : System.out.println("This is a Queens bound train!");
					break;
			default:
				System.out.println("I'm not sure where that train goes...");

		}
	}
	}
   
