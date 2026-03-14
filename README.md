# java-test-0001-final-16431-shivani
Final Project Assignment - This repository contains the complete final project code and documentation.
```java
  public class Pattern {
    public static void main(String[] args) {
        int n = 5;
   public class Pattern {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= n - i; j++) {
                System.out.print(" ");
            }
            System.out.print("*");
            for (int j = 1; j <= 2 * i - 3; j++) {
                System.out.print(" ");
            }
            if (i > 1) {
                System.out.print("*");
            }
            System.out.println();
        }
        for (int i = n - 1; i >= 1; i--) {
            for (int j = 1; j <= n - i; j++) {
               System.out.print(" ");
            }
            System.out.print("*");
            for (int j = 1; j <= 2 * i - 3; j++) {
                System.out.print(" ");
            }
            if (i > 1) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
