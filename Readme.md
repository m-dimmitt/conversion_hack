## How can i quickly perform conversions?

#### Hex to binary.
<pre>
 1 1 1 1       example: C2 = 1100 0010
 _ _ _ _
 8 4 2 1       (note) adds up to 15 when 1111. 0000 is the 16'th value.
</pre>

## Binary to decimal.
<pre>
256 128 64 32 16 8 4 2 1     adds up to 511 . all zero's makes 512'th value.
 1   1  1  1  1  1 1 1 1     (note) this requires 9 binary digits.
</pre>

## Decimal to binary.
<pre>
example: 9  
         4 1 
	 2 0
	 1 0
	 0 1

Divide by two, first result is the least significant bit.
remainders... provide the numbers.
division will always end with o divided by remainder 1.
</pre>


TA = target address

direct addressing - sic
simple addressing - pointer in c
immediate addressing - TA is operand value ... no mem refrance.
Simple addressing - TA is location of address.
