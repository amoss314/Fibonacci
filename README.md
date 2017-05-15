# Fibonacci
The Famous Fibonacci sequence

public class Fibonacci {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		//My Fibonacci series
		int a=0;// seed number
		int b=1;// seed number
		int c;// seed number
		int count=13;// Count of numbers needed
		
		System.out.println(a);// Printing out first 2 numbers in the series
		System.out.println(b);
		
		for(int i = 2; i < count; i++){// for loop, count is 13 numbers and less. adding value to each number
			c = a + b;
			a = b;
			b = c;
			
			System.out.println(c);
		}
	}
}
