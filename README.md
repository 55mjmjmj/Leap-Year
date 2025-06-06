import java.util.Scanner;
public class LeapyearA2 
{
	public static void main (String [] args)
	{
		Scanner scan=new Scanner(System.in);
		System.out.println("Enter year");
		int year=scan.nextInt();
		// checking whether year is divisible by 4
		if(year%4==0)
			{
				// checking whether year is not divisible by 100
				// or year is divisible by 400
				if(year%100!=0 || year%400==0)
					{
						System.out.println(year+ "is a leap year");
					}
				else
					{
						System.out.println(year+ "is not a leap year");
					}
			}
				else
					{
						System.out.println(year+ "is not a leap year");
					}
	}
}
