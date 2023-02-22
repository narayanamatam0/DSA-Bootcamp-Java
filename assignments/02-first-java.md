# [Video Link](https://youtu.be/TAtrPoaJ7gc)

## Write Java programs for the following:

1. Write a program to print whether a number is even or odd, also take
input from the user.
2. Take name as input and print a greeting message for that particular name.
3. Write a program to input principal, time, and rate (P, T, R) from the user and
find Simple Interest.
4. Take in two numbers and an operator (+, -, *, /) and calculate the value.
(Use if conditions)
5. Take 2 numbers as input and print the largest number.
6. Input currency in rupees and output in USD.
7. To calculate Fibonacci Series up to n numbers.
8. To find out whether the given String is Palindrome or not.
9. To find Armstrong Number between two given number.
program:


import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		int n1=s.nextInt();
		int n2=s.nextInt();
		for(int i=n1;i<n2;i++)
		{
		    int check,rem,sum=0;
		    check=i;
		    while(check!=0)
		    {
		        rem=check%10;
		        sum+=(rem*rem*rem);
		        check/=10;
		    }
		    if(sum==i)
		    {
		        System.out.println(" "+i+"is amstrong number");
		    }
		}
	}
}


