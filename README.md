# Adding-two-numbers-by-using-Java

import java.util.Scanner;

public class AddingtwoNumbers {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter Two Number :");
		int a = input.nextInt();
		int b = input.nextInt();
		int c = a+b;
		System.out.println("The Result of two Numbers : " +c);
		input.close();
	}
}
