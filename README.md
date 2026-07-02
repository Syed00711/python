# python
python notes
Arithmatic:
floor division: // integer output to lowest integer
expotential: **
bitwise:
order parentheses>exponential>dividion>multipliction>addition>substraction
functions: round,abs,len,type,int,float,str,round(number, ndigits)
string: single quotes or double quotes(when single quote in string)
concatenation:+
string multiplication: *
large number: _     1_000_000

Round half to even (also called banker's rounding) is a rounding rule Python uses when a number is exactly halfway between two possible rounded values
round(2.35, 1)   # 2.4
round(2.25, 1)   # 2.2
round(1.5)   # 2
round(2.5)   # 2
round(3.5)   # 4
round(4.5)   # 4
round(5.5)   # 6

Bitwise operators in Python

Bitwise operators work on the binary representation of integers.

Operator	 Symbol	 Description	Example
AND	         &	         Sets a bit to 1 only if both bits are 1	5 & 3 → 1
OR	         |	         Sets a bit to 1 if either bit is 1	5 | 3 → 7
XOR	         ^	         Sets a bit to 1 if the bits are different	5 ^ 3 → 6
NOT	         ~	         Inverts all bits	~5 → -6
Left Shift	 <<	         Shifts bits left by specified positions	5 << 1 → 10
Right Shift	 >>	         Shifts bits right by specified positions	5 >> 1 → 2

Python operator precedence (highest to lowest)
Precedence	         Operators	           Description
1(Highest)	             ()	                  Parentheses
2	                       **	                  Exponentiation
3	                     +x, -x, ~x	            Unary plus, minus, bitwise NOT
4	                     *, /, //, %	          Multiplication, division, floor division, modulus
5	                        +, -	              Addition, subtraction
6	                       <<, >>	              Bitwise shifts
7	                         &	                Bitwise AND
8	                         ^	                Bitwise XOR
9	                        `	`
10	                ==, !=, <, <=, >, >=,      is, is not, in, not in	Comparisons
11	                       not	               Logical NOT
12	                       and	               Logical AND
13	                       or	                 Logical OR
14 (Lowest)	          =, +=, -=, etc.	          Assignment



