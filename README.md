# starprint-4-

package problem.pkg4.star.right;

import java.util.Scanner;


public class Problem4StarRight {

    
    public static void main(String[] args) {
        
          int i,j,star;
        Scanner input=new Scanner(System.in);
        System.out.println("enter the number");
        star=input.nextInt();
        for(i=4;i>=1;i--)
        {
             for(j=1;i>=j;j++)
            {
                System.out.print("* ");
            }
             
              System.out.println(" ");
        }
        
        
    }
    
}
