# exponential-numbers
Java101_20 Calculating exponential value by given base and exponents with for loop

https://www.patika.dev/tr

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    
	    int base, exponent, i, total;
	    
	    Scanner input=new Scanner(System.in);
	    System.out.print("Enter base number : ");
	    base=input.nextInt();
	    
	    System.out.print("Enter exponent number : ");
	    exponent=input.nextInt();
	    
	    total=1;
	    for(i=1 ; i<=exponent ; i++){
	        total*=base;
	        
	    }
	    System.out.print(base+" to the power "+exponent+" is : "+total);


	}
}
