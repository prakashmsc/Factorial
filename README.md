# Factorial
package com.payilagamtest.java;

import java.util.Scanner;

public class Factorial {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("WRITE ANY TO CALCULATE FACTORIAL :");
		Scanner sc=new Scanner(System.in);
		int a=sc.nextInt();
		int fact=1;
		
			for(int c=1;c<=a;c++){
				fact=fact*c;
				
			}
			System.out.println("your answer is :"+fact);
		}
		

	}
