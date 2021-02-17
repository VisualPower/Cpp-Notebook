# Cpp-Notebook

// Written in C++

/*
	Version 1.0

	Last Revised 2/8/2021
	Author VisualPower

	Contact: geckoplayz4@gmail.com
*/

#include <iostream>				// Using iostream because this header file has cout/cin.
#include <string>				// This is not only a calculator but a playground for code so using this header file to include sentence capability.

using namespace std;            // Tells computer the code for cout etc.

int main()						// Code goes in this container and can be ended by using return 0 only if int main() is used.
{
	// Sentence

	string MySring = "Made by VisualPower";     // Using the string header file as a variable.

	// Calculator

	double sum1, sum2, result;  // Using double because it can hold values upto 15 - 15.
	char op;					// Assigning operator to a "character" - type variable.
	
	cout << "\nCalculator - Enter a number: ";	  // Cout asking for a number to work with.
	cin >> sum1;                                  // Enter a number at will.
	cout << "Enter a operator: ";				  // Cout asking for a operator to apply on the numbers.	
	cin >> op;									  // Enter a operator at will.
	cout << "Enter another number: ";			  // Cout asking for another number to work with.
	cin >> sum2;								  // Enter another number at will.

	if (op == '+') result = sum1 + sum2;		  // If operator + is instered then perform the operation "+".
	if (op == '-') result = sum1 - sum2;		  // If operator + is instered then perform the operation "-".
	if (op == '*') result = sum1 * sum2;		  // If operator + is instered then perform the operation "*".
	if (op == '/') result = sum1 / sum2;		  // If operator + is instered then perform the operation "/".

	cout << result;                               // Cout will put out the result.

	// Formula Practice Conversion of Mins = Secs

		int mins, secs;							  // Defines and gives a life to mines/secs.

		cout << "Enter minutes: ";				  // Cout will ask for mins.	
		cin >> mins;							  // Enter minutes.

		secs = mins * 60;						  // Formula for seconds conversion.
		mins = secs % 60;						  // Formula for minutes conversion.


		cout << secs << " seconds ";			  // Cout will present the answer.	

		cout << MySring;                              // Credit.
	

	return 0;                                     // Teminate the program and stop it.

	

}
