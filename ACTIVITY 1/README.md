public class Main {
    public static void main(String[] args) {
        int num1 = 10;
        int num2 = 5;
        char operator = '+'; 

        int result = 0;

        if (operator == '+') {
            result = num1 + num2;
            System.out.println("Sum = " + result);
        } else if (operator == '-') {
            result = num1 - num2;
            System.out.println("Difference = " + result);
        } else if (operator == '*') {
            result = num1 * num2;
            System.out.println("Product = " + result);
        } else if (operator == '/') {
            if (num2 != 0) {
                result = num1 / num2;
                System.out.println("Quotient = " + result);
            } else {
                System.out.println("Error: Division by zero!");
            }
        } else {
            System.out.println("Invalid operator!");
        }
    }
}
