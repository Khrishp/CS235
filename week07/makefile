###############################################################
# Program:
#     Assignment 07, LIST
#     Brother Kirby, CS235
# Author:
#     Garrett Smith & Aiden Reid & Ian Stubbs
# Summary:
#     TO DO
# Coding Time:
#     Pair: 
#     Garrett: 
#     Ian:
#     Aiden:
#
# The most difficult part:
#     Aiden: 
#     Garrett:
#     Ian: 
###############################################################

##############################################################
# The main rule
##############################################################
a.out: list.h assignment07.o fibonacci.o wholeNumber.o
	g++ -o a.out assignment07.o fibonacci.o wholeNumber.o -g  -std=c++11
	tar -cf assignment07.tar *.h *.cpp makefile

##############################################################
# The individual components
#      assignment07.o : the driver program
#      fibonacci.o    : the logic for the fibonacci-generating function
#      <anything else?>
##############################################################
assignment07.o: list.h assignment07.cpp
	g++ -c assignment07.cpp -g  -std=c++11

fibonacci.o: fibonacci.h fibonacci.cpp list.h
	g++ -c fibonacci.cpp -g  -std=c++11

wholeNumber.o: wholeNumber.h wholeNumber.cpp list.h
	g++ -c wholeNumber.cpp -g  -std=c++11

