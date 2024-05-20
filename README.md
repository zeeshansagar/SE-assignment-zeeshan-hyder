import java.util.Scanner;

public class AdditionSubtraction {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the user
        Scanner scanner = new Scanner(System.in);
        
        // Prompt the user to enter the first number
        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();
        
        // Prompt the user to enter the second number
        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();
        
        // Calculate the addition of the two numbers
        double sum = num1 + num2;
        
        // Calculate the subtraction of the two numbers
        double difference = num1 - num2;
        
        // Display the results
        System.out.println("The sum of the two numbers is: " + sum);
        System.out.println("The difference of the two numbers is: " + difference);
        
        // Close the scanner
        scanner.close();
    }
}
