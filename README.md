
import java.util.Scanner;

 public class Main {
    public static void main(String[] args) {
        Product p = new Product();
        
         // Task 3: Call the method product(int x, int y)
        System.out.println("Product of 5 and 10 is: " + p.product(5, 10));
        
        // Task 4: Call the method product(int x, int y, int z)
        System.out.println("Product of 2, 3, and 4 is: " + p.product(2, 3, 4));
        
        // Task 5: Call the method product(double x, double y)
        System.out.println("Product of 2.5 and 3.5 is: " + p.product(2.5, 3.5));
    }
    
    public static class Product {
        // Task 3: Method with int parameters
        public int product(int x, int y) {
            return x * y;
        }
        
        // Task 4: Overloaded method with int parameters
        public int product(int x, int y, int z) {
            return x * y * z;
        }
        
        // Task 5: Overloaded method with double parameters
        public double product(double x, double y) {
            return x * y;
        }
    }
}

