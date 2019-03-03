# MidTerm-Q3
import java.util.*;
public class fibonacci {



public static void main(String args[]) {
		
		System.out.println("Enter fibonacci outcomes ");
		Scanner scan = new Scanner(System.in);
		int max = scan.nextInt();
		System.out.println("The fibonacci numbers are");
		int a, b, sum, i;
		a = 1; 
		b = 2;
		for (i = 1; i <= max; i++) {
			System.out.println(a);
			sum = a + b;
			a = b;
			b = sum;
		}
	}
}
