package Currency_Converter;
import java.util.*;
public class currency {
	public static void main(String[]args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("choose the currency and enter the number");
		System.out.println("1-India rupee");
		System.out.println("2-Usa Doller");
		System.out.println("3-Canada Doller");
		System.out.println();
		System.out.println("enter the convert currency");
		int a=sc.nextInt();
		
		switch (a) {
		  case 1:
		    System.out.println("India rupee");
		    break;
		  case 2:
		    System.out.println("Usa Doller");
		    break;
		  case 3:
		    System.out.println("Canada Doller");
		    break;
		    default:
		    	System.out.println("invaild enter");
		    	break;
		}
		System.out.println("enter the amount");
		int b=sc.nextInt();
		switch (a) {
		  case 1:
			  System.out.println("convert amount is");
		    System.out.println(b*1);
		    break;
		  case 2:
		    System.out.println(b*82);
		    break;
		  case 3:
		    System.out.println(b*100);
		    break;
		}
		
	}
}
