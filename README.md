
public class HelloWorld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello World!");
	}

}


public class Arrays {

	public static void main(String[] args) {
		//Variable Initialization
		String[] alpha = {"Alpha", "Beta", "Charlie"};
		int[] 	 num   = {1,2,3,4,5};
		
		//Print of individual elements of string array
		System.out.println(alpha[0]);
		System.out.println(alpha[1]);
		System.out.println(alpha[2]);
		//Loop to iterate through each element
		for (int i = 0; i <= 2; i++) {
            System.out.print(alpha[i] + " ");
        }
		//Punctuation for console readability
		System.out.println();
		
		//Print of individual elements of integer array
		System.out.println(num[0]);
		System.out.println(num[1]);
		System.out.println(num[2]);
		System.out.println(num[3]);
		System.out.println(num[4]);
		//Loop to iterate through each element
		for (int i = 0; i <= 4; i++) {
            System.out.print(num[i] + " ");
        }
		
	}

}


public class Loops {

	public static void main(String[] args) {
		//Variable Initialization
		int i = 0;
		
		//Example of a While Loop
		System.out.println("While Loop: ");
		while(i<=10)
		{
			//Example of an if/else statement
			if(i == 10)
				System.out.print(i);
			else
			System.out.print(i + ", ");
			i++;
		}
		//Punctuation for Console readability
		System.out.println();
		
		//Example of a For Loop
		System.out.println("For Loop: ");
		for(int j = 0;j <= 10; j++)
		{
			//Example of an if/else statement
			if(j == 10)
				System.out.print(j);
			else
			System.out.print(j + ", ");
		}

		
	}

}


public class NestedLoops {

	public static void main(String[] args) {
		//Variable Initialization
		String s = "*";
		
		//Example Loop #1
			//Outer Loop
		for(int i = 1; i<=3;i++) 
		{
			System.out.print("Week " + i+": ");
			
			//Inner loop
			for(int j = 1; j<=3;j++) 
				System.out.print(" Day: " + j);
			
			//Punctuation for Console readability
			System.out.println();
		}
		
		//Punctuation for Console readability
		System.out.println();
		
		//Example Loop #2
			//Outer loop
		for(int i = 1; i<=5;i++) 
		
		{		
			//Inner loop
			for(int j = 1; j<=i;j++) 
				System.out.print(s);
			
			//Punctuation for Console readability
			System.out.println();
		}
			
	}

}
