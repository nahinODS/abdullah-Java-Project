import java.util.Scanner;

import java.util.Scanner;
public class userinput {
     public static void main(String[] args) {
         Scanner sc  = new Scanner(System.in);
         System.out.print("Enter your age: ");
         int age = sc.nextInt();
         System.out.println("Your age is: " + age);
         sc.close();


    }
}
