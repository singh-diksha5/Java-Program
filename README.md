//Maximum between two numbers using ternary operator
import java.util.Scanner;

public class MaxNumber {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        int num1 = input.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = input.nextInt();

        int max = (num1 > num2) ? num1 : num2;

        System.out.println("Maximum number is: " + max);
    }
}