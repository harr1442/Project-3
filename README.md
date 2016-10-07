# Project-3
import java.util.Random; 
import java.util.Scanner;

public class Sonar {
	public static void Generator(int xLocation, int yLocation, int zLocation) {
		Random random = new Random();
		int Location = 0;
		int xLocation = random.nextInt(10) + 1;
		int yLocation = random.nextInt(10) + 1;
		int zLocation = random.nextInt(10) + 1;
		
		Location = (xLocation* 100) + (yLocation * 10) + zLocation;
		
		return Location;
	}
	
	public static int main(int userGuesses) {
		Scanner scnr = new Scanner(System.in);
		userGuesses = scnr.nextInt();
		int n  = 1; 
		
		System.out.println("*** Find the Submarine version 1.0 by Alana Harris ***" + \n);
		System.out.println("The computer has placed the submarine");
		System.out.println("You have 5 guesses to locate the submarine");
		
		while (n <= 5) {
			System.out.print("Enter the location to ping (XYZ): " + userGuesses);
			if (userGuesses == Generator) {
				System.out.println("You found the submarine in " + n + " tries");
			}
			else if()
			}
		}
	}
