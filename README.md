# java-test-0001-final-16431-shivani
Final Project Assignment - This repository contains the complete final project code and documentation.
```java
public class PatternPrinter {
    public static void main(String[] args) {
        int n = 5; // Controls the height of one half of the pattern

        // Upper half of the pattern
        for (int i = 1; i <= n; i++) {
            // Print leading spaces
            for (int j = 1; j <= n - i; j++) {
                System.out.print(" ");
            }
            // Print first star
            System.out.print("*");
            // Print middle spaces
            for (int j = 1; j <= 2 * i - 3; j++) {
                System.out.print(" ");
            }
            // Print second star if not the first row
            if (i > 1) {
                System.out.print("*");
            }
            System.out.println();
        }

        // Lower half of the pattern
        for (int i = n - 1; i >= 1; i--) {
            // Print leading spaces
            for (int j = 1; j <= n - i; j++) {
                System.out.print(" ");
            }
            // Print first star
            System.out.print("*");
            // Print middle spaces
            for (int j = 1; j <= 2 * i - 3; j++) {
                System.out.print(" ");
            }
            // Print second star if not the last row of this half
            if (i > 1) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
