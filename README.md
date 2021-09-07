import java.util.Scanner;
public class BiggestNumber
{
  public static void main(String[] args)
 {
    int n,y,z;
    Scanner s=new Scanner(System.in);
    System.out.print("Enter the first number:");
    n=s.nextInt();
    System.out.print("Enter the second number:");
    y=s.nextInt();
    System.out.print("Enter the third number:");
    z=s.nextInt();
    if(n>y&&n>z)
    {
    System.out.println("The Largest Number is:"+n);
    }
    else if(y>n&&y>z)
    {
     System.out.println("The Largest Number is:"+y);
    }
    else
    {
    System.out.println("The Largest Number is:"+z);
    }
  }
}
