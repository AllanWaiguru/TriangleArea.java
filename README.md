# TriangleArea.java
import java.util.Scanner;

public class TriangleAreaCalculator {
    public static void main(String[] args) {
        calculateTriangleArea();
    }

    public static void calculateTriangleArea() {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the base of the triangle: ");
        double base = input.nextDouble();
        System.out.print("Enter the height of the triangle: ");
        double height = input.nextDouble();

        double area = (base * height) / 2;

        displayTriangleArea(area);
    }

    public static void displayTriangleArea(double area) {
        System.out.println("The area of the triangle is: " + area);
    }
}
