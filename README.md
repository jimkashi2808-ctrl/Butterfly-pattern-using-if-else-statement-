# Butterfly-pattern-using-if-else-statement-
import java.util.*;
class Butterfly
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        
        while(n<0)
        {
            System.out.println("Invalid input");
            break;
        }
        for(int i=1;i<=n;i++) 
        {
            for(int j=1;j<=n*2;j++)
            {
                if(i==j||j==1||j==(n*2)||(i+j)==(n*2)+1||j<=i||(i+j)==(n*2)+2||((i+j)<=(n*2)*2)&&(i+j)>(n*2)+1)
                {
                    System.out.print("*");
                }
                else
                {
                    System.out.print(" ");
                }
            }
                System.out.println();
            }
        for(int i=n;i>=1;i--) 
      {
          for(int j=1;j<=(n*2);j++)
          {
            if(i==j||j==1||j==(n*2)||(i+j)==(n*2)+1||j<=i||(i+j)==(n*2)+2||((i+j)<=(n*2)*2)&&(i+j)>(n*2)+1)
                {
                    System.out.print("*");
                }
                else
                {
                    System.out.print(" ");
            }
        }
            System.out.println();
       }
        
    
}
    }

        
