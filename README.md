# Radio Station (Classical Ben System)

Software was created using Pascal (Delphi). Please use Delphi 7 or better such as Delphi Community Edition in order to open source files of project.

You can find full description of Ben System in the following link: https://www.academia.edu/43789675/Bilbut_Security_Tools

Please keep in mind that Real Time Encryption Method uses a variant of Ben System. This repository proves the classical Ben System.

As mentioned in the original document, I got this idea from a broken CD player.

The idea consists of:
1) A constant flow of zeroes (0) and ones (1).
2) A mathematical function: This software uses square of a number.
3) A time interval to apply mathematical function.
4) An incremental counter at a given speed.

Procedure:
Verify every a constant time interval such as one (1) second that the square of the counter is a whole number and then add to a list current digit of the flow.

Uses:
This method has multiple applications in cryptography (not analog) such as in the Real Time Encryption Method.
