# Collatz-s_question
the_3n+1_conjecture
/*
The goal here is to implement a program that 
will generate a list of numbers given user input 
of a natural number n. The list will be generated based
off of Collat'z question, the (3n + 1)

Some general guidelides:
							*Need to scan the list of numbers to check for the 
							sequence 1,4,2,1....
							
							*Program should list how many numbers are in the 
							 Generated list upto the never ending sequence
							 *Implement decent input validation for the natural
							 number.
							 
				_______________________________________________________________________			 
							 *Show use of functions
							 
							 Functions:
											1. User input and validation, check and decide if n 
												is even or odd and return.
											
											2.  We have two rules for the final portion:
												A. if n is even, next natural number is n/2
												B. if n is odd, then next natural number is 3n+1
											
											3. Keep it simple, The rules will be applied and n replaced
												with the result of each applied rule.
											
											4. Each result will be stored in a list, this list should be
											   a function, which is called after each rule is applied.
											   
											5. The program will end once we have the sequence 1,4,2,1 //need to keep it short for now
																									  // so check for 1,4,2,1,4,2,1 then end
											6. Print the sequence from the stored list in the list function, 
											   Print how many numbers are in the list minus the two sequences 
											   we use to end the program.
							
							 
							 
				_______________________________________________________________________			 
							 
					PROGRAM PROBLEM ANALYSIS - EXECUTION CYCLE
				_________________________________________________________
				
				PROCESS OF PROBLEM SOLVING:		-Analyze the problem
											    -Outline problem Requirements
												-Design steps ---> ALGORITHM
												

												
												-How to generate the list
												-Can the size be calculated

												-*- Try to check the index of the vector array:
												if(([i]- [i]-(1)) == 1, && [i] - 2 == 4, &&
													[i] - 3 == 2 )
												
												Try starting there, index [i] will be the next caculated value, the values 
												will be stored, and therefore checked for the sequence 1,4,2,1,4,2,1
												
										So, I need an array size. Ideally an infinite limit but C++ may not like this.

												
												
												
												
*/
















// Code as of now, have to work slow and look up rules for C++ along the way
// And keep notes on how to implement algorithm
/*
#include "stdafx.h"
#include <iostream>
#include <iomanip>
#include <string>

using namespace std;

int getUserInput(int input);


int main()
{
    return 0;
}

int getUserInput()
{






}











*/
