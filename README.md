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

program-2
##Single integer



public class Single2 {

	public static void main(String[] args) {
		int a=5;
		int v=1;
		
		
		for(int i=1;i<=a;i++)
		{
			System.out.print(v +" " );
			v=v+2;
		}
	}

}


program-3
## single3




public class Single2 {

	public static void main(String[] args) {
		int a=4;
		int v=1;
		
	
		for(int i=1;i<=a;i++)
		{
			System.out.print(v +" " );
			v=v+2;
			
		}
	
		
	}

}


program-4
## Series

import java.util.Scanner;
public class Series {


public static void main(String[] args) {
    Scanner s=new Scanner(System.in);
int []series= {1,2,3,4,5,6,7,8,9};
int []input=new int[100];
int []count= new int[series.length];


    System.out.println("enter no. of elements in input");
    int n=s.nextInt();
    System.out.println("enter elements");
    for(int i=0;i< n;i++)
    {
        input[i]=s.nextInt();
    }
    for(int j=0;j< n;j++)
    {
        for(int i=0;i< series.length;i++)
        {
            if(input[j] % series[i]==0)
                count[i] +=1;
        }
    }
    for(int i=0;i< series.length;i++)
    {
        System.out.print(series[i]+" : "+count[i]+ ", " );
    }

}
}
