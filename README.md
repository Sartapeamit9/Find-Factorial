# Find-Factorial
import java.util.Scanner;
public class FindFactorial
{
int i,number,fact=1;
Scanner sc=new Scanner(System.in);
System.out.println("Enter a number To Find Factorial");
number=sc.nextInt();
for(i=1;i<=number;i++)
{
fact=fact*i;
}
System.out.println("FActorial of Given Is "fact);

}
