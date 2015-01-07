Single Line Caesar Cipher
===

This is a Caesar Cipher I wrote in Python using just one line of code. It uses the string module's ascii_lowercase constant to build its alphabet.

usage: python caesar.py number_to_shift text to shift

It can shift either direction. Any number greater than the length or less than the negative length of the alphabet will wrap around, e.g., 27 will become 1. Any whitespace and punctuation is left unchanged. Output is in lowercase.

**Examples**

input:      python caesar.py 2 test              
output:     vguv

input:      python caesar.py 10 hello world                    
output:     rovvy gybvn

input:      python caesar.py -3 Test Caesar Cipher                 
ouptut:     qbpq zxbpxo zfmebo

**Requirements**                   
Python 3
