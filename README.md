# numbers
 import java.util.Scanner;
 public class Number 
{
public static void main(String[] args) 
{
  Integer i;
  Scanner s = new Scanner(System.in);
  System.out.print("Enter the number:");
  i= s.nextInt();
  if(i > 0)
{
  System.out.println("The given number "+i+" is Positive");
}
  else if(i < 0)
{
  System.out.println("The given number "+i+" is Negative");
}
  else
{
  System.out.println("The given number "+i+" is Zero");
}
}
}
