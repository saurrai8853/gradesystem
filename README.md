# gradesystem
//Write a program that takes a student's grade as input and 
//prints out their corresponding letter grade based on the 
//following grading scale:
//
//A: 90-100
//B: 80-89
//C: 70-79
//D: 60-69
//F: Below 60


package mypackage;

import java.util.Scanner;

public class BasicProgram01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Enter stundent's grade:");
		Scanner sc=new Scanner(System.in);
		int mark=sc.nextInt();
		if(mark<100 && mark>90) {
			System.out.println("A:"+mark);
		}
			else if(mark<89 && mark>80) {
				System.out.println("B:"+mark);
			}
			else if(mark<79 && mark>70) {
				System.out.println("C:"+mark);
				}
				else if(mark<69 && mark>60) {
					System.out.println("D:"+ mark);
				}
				else{
					System.out.println("F:"+mark);
		}

	}

}
