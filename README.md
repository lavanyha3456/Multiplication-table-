# Multiplication-table-
import java.util.Scanner;

public class MultiplicationTable {

    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter a number
        System.out.print("Enter a number to print its multiplication table: ");
        int num = scanner.nextInt();

        // Generate and display the multiplication table
        for (int i = 1; i <= 10; i++) {
            System.out.printf("%d * %d = %d%n", num, i, num * i);
        }
    }
}

output:
Enter a number to print its multiplication table: 7
7 * 1 = 7
7 * 2 = 14
7 * 3 = 21
7 * 4 = 28
7 * 5 = 35
7 * 6 = 42
7 * 7 = 49
7 * 8 = 56
7 * 9 = 63
7 * 10 = 70
