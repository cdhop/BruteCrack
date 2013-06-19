# BruteCrack

A password brute force cracking program implemented in Java

This program is more a demonstration of principle, rather than an attempt to crack real-world passwords.  
The program will (with processing power and time) crack a password which has been encrypted using the MD5 cryptographic hash.

The program accepts a MD5 hash as a parameter and progresses through a series of ever larger combinations until it finds a value (password) whose hash matches the hash which was passed in the parameter.
The program will then output the password and the number of seconds it took to find a match.

Hopefully, no real-world passwords are still hashed and stored using MD5.  This program demonstrates how trivial it is to defeat such an approach.

This program also demonstrates the security benefit of using longer length passwords.  For each additional character used, the possible combinations that a brute force approach must try is increased by an additional power of the total range of characters tried.
This can dramatically increase the difficulty of 'cracking' a password. 
