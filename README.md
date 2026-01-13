//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
import java.util.Scanner;
/*System.out.println("Java");
//
 double weight;
 double centimeters = 0;

 System.out.print("Enter your height with centimeter measure: ");
 centimeters = input.nextDouble();

 System.out.print("And, enter your weight: ");
 weight = input.nextDouble();

 if(centimeters>=140 && centimeters<=240)
 {
     System.out.println("Your height is "+centimeters);
     System.out.println("Your weight is "+weight);
     if(weight <=(centimeters-100))
     {
         System.out.print("Your weight is ideal");
     }
 }
 else{
     System.out.print("You must be enter between 140 and 240 cm!");
 }
*/
import java.util.Scanner;

public class Main {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
/*
        Scanner input = new Scanner(System.in);

        for(int row = 1; row<= 5; row++)
        {
            for(int col = 1; col<= 5; col++)
                System.out.print(row*col + "\t");
            System.out.println();
        }
        int i, j;
        for(i = 6; i>= 1; i--)
        {
            for(j = 0; j< i; j++)
                System.out.print(i-j + " ");
            System.out.println();
        }


        System.out.println("Enter your number * lines you want, that it followed by #: ");
        int user= input.nextInt(), M=0, r = 0, u = 0;

        if(user <0)
            user = user* -1;

        for(int N = user; N>= 1; N--)
        {
            for(M = N; M>= 1; M--)
                System.out.print("*");

            r++;
            u = r;
            while(u!=0)
            {
                System.out.print("#");
                u--;
            }

            System.out.println();
        }

        int num = input.nextInt(); // 4321
        while (num>0)
        {
            int d = num%10;
            System.out.print(d); // 4321
            num = num / 10;
        }
*/
        int first, second, total;
        System.out.print("Enter the first number:");
        first = input.nextInt();

        System.out.print("Enter the second number:");
        second = input.nextInt();

        total = first + second;
        System.out.printf("%d+%d=%d%n", first, second, total);


    }
}
