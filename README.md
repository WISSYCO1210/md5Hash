The Reverse Hash Application
============================

This Application was built with the certificate i achieved with Coursera
 "Building Web Applications in PHP" with Mr. Charles Russell Severance

This is the Description of the application : 

This application uses a very simple brute force attack to 
"reverse" an MD5 hash.  It is really not reversing the hash
at all as that would be impossible.  Instead it knows that 
the original pre hash text was a lower case character string with 
exactly two characters.

So the application uses two nested loops and tests all 
26*26 combinations of two lower case letters, and computes the
hashes of those values and checks to see if the computed hash
matches.


This is a lesson in how easy it is to crack short passwords
with a limited alphabet.  While this works well to crack 
very short passwords it is not practical as password 
length grows.

