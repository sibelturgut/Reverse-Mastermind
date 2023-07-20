# Reverse-Mastermind
Think of the classical Mastermind game, but with 6-digits and program is the Guesser

  This is my first "big" project. I completed it at the date 26.12.2022 for my CS class project.
  Mastermind with 6-digits; codemaker provides a code with 6 digits -such as 123456- and the codebreaker tries to guess
the code with the help of the feedbacks given from codemaker according to the guessed numbers. Feedbacks can only be given in
one form which is (correct numbers in correct places, correct numbers in wrong places). To demonstrate, if the code number is 123456 and
I guess 123458, the feedback will be 5,1 since 5 of the digits are correctly placed but 8 is in the wrong place so it is 5,1.

  So, in this program, user is the codemaker and the program is the codebreaker. Program starts the game with an initial guess, and user
provides a feedback. Then, program makes another guess according to the feedback and gets another feedback and goes on until it finds
the code.
