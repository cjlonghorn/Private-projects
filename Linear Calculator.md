//for class newClass

import java.util.Scanner;


public class NewClass
{
public static void main(String[] args) 
  {
    Scanner scan = new Scanner(System.in);
    System.out.println("Welcome to the linear systems calculator please look below.");
    System.out.println("We will be working to find the value of X in the equation AX + B = CX + D");
    System.out.println("Please enter the value of A");
    float A = scan.nextFloat();
    System.out.println("Please enter the value of B");
    float B = scan.nextFloat();
    System.out.println("Please enter the value of C");
    float C = scan.nextFloat();
    System.out.println("Please enter the value of D");
    float D = scan.nextFloat();
    float BD = B - D;
    float CA = C - A;
    if(CA == 0) {
    System.out.println("Sorry x has no solution");
}
  float end = BD / CA;
  System.out.println("X = " + end);
  float endA = A * end;
  float endAB = endA + B;
  System.out.println("y = " + endAB);
}
}
