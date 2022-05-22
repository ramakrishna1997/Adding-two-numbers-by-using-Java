# Adding-two-numbers-by-using-Java

import java.util.Scanner;

public class AddingtwoNumbers {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter First Number :");
		int a = input.nextInt();
		System.out.println("Enter Second Number : ");
		int b = input.nextInt();
		System.out.println("Please Enter Operation ");
		String operation = input.next();
		int result =0;
		switch(operation) {
		case "+":
			result=a+b;
			break;
		case "-":
			result=a-b;
			break;
		case "*":
			result=a*b;
			break;
		case "/":
			result=a/b;
			break;
		case "%":
			result=a%b;
			break;
		default:
			System.err.println("Invaild operation");
		}
		System.out.println(result);
		input.close();
	}
}
