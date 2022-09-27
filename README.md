# program-1.java
import java.util.Scanner;

public class Calculstor {

	public static void main(String[] args) {
		
Scanner s=new Scanner(System.in);
System.out.println("please enter first value" );
double num1=s.nextDouble();
System.out.println("please enter second value" );
double num2=s.nextDouble();
System.out.println("please select which action should be perform" );
System.out.println("1=addition,\n 2=subtraction,\n 3=multiplication,\n 4=divition" );
int operator=s.nextInt();

switch(operator)
{
case 1:System.out.println("addition="+(num1+num2));
       break;
case 2:System.out.println("subtraction="+(num1-num2));
break;
case 3:System.out.println("multiplication="+(num1*num2));
break;
case 4:System.out.println("divition="+(num1%num2));
break;
default:System.out.println("plese enter valid option");
}
	}

	}

