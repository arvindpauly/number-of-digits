# number-of-digits
import java.util.Scanner;
public class num {
	public static void main(String[]arg){
	Scanner ab=new Scanner(System.in);
	int a;
	int count=0;
	System.out.println("enter the number");
	a=ab.nextInt();
	while(a!=0)
	{
		a=a/10;
		count++;
}
System.out.println("tne number of digits"   +count );	
}
	

}

 
