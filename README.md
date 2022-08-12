# A
LAB
import java.util.Scanner;

public class Calculator
{
    public static void main(String[]args){
    Scanner cal = new Scanner(System.in);


        int number1;
		int number2;
		int answer;

		System.out.println("select operator");
		System.out.println("1.add");
		System.out.println("2.sub");
		System.out.println("3.mult");
		System.out.println("4.div");

		int operator = cal.nextInt();

		System.out.println("enter the number1:");
		number1 = cal.nextInt();
		System.out.println("enter the number2:");
		number2 = cal.nextInt();

		if(operator == 1){
		     answer = (number1+number2);
			 System.out.println("answer:" + answer);

			 }

		else if(operator == 2){
            answer = (number1-number2);
			 System.out.println("answer:" + answer);

			 }		


		else if(operator == 3){
            answer = (number1*number2);
			 System.out.println("answer:" + answer);

			 }		


		else if(operator == 4){
            answer = (number1/number2);
			 System.out.println("answer:" + answer);

			 }		


		else{
		     System.out.println("enter correct operator");

		}
	}	
}  	
