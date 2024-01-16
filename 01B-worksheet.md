# Lab 01
## Worksheet 01B
### Base Conversion
Feel free to refer back to Lecture 01 for additional assistance.

Expanded positional notation is a sum of terms of the form: $$\large \text{value}\,\times\,\text{base}^\text{position}$$
Below is a table for converting between decimal, hex, octal, and binary:
![[DecimalHexOctalBinaryTableComparison.png|600]]

- To convert a number of base $b$ to decimal (base 10), expand the base $b$ number using positional notation, then calculate the sum.
- To convert from decimal to another base $b$, divide $n$ by $b$ repeatedly until the quotient $q$ is zero, and take the remainders. This is the "systematic" method.
- Decimal to binary conversion is easier with the nonsystematic "powers of 2" method:
	1. Find the largest power of $2$ less than the number you wish to convert (e.g., $2^k < n$).
	2. Subtract that number $(n-2^k)$.
	3. Add a $1$ in the corresponding place in the binary string.
	4. Repeat.

For reference, below are the first 16 powers of two:
$$\displaylines{\!\small\begin{array}{|c|c|}\hline
2^0 & 2^1 & 2^2 & 2^3 & 2^4 & 2^5 & 2^6 & 2^7 & 2^8 & 2^9 & 2^{10} & 2^{11} & 2^{12} & 2^{13} & 2^{14} & 2^{15} & 2^{16}\\\hline
1&2&4&8&16&32&64&128&256&512 & 1024&2048&4096&8192&16384&32768&65536
\\\hline\end{array}}$$

To convert from binary to octal or hexadecimal, simply group the bits of the binary number into groups of 3 or 4, respectively. Then, convert each group into the corresponding digit using the table provided above.

### Binary to Decimal Conversion
#### (1)
Convert $1011_2$ to decimal using expanded positional notation. Show your work.

<br><br><br><br><br><br>

#### (2) 
Convert the following binary number to octal. Show your work. $$\texttt{0 1 0 1 1 1 0 0 1 0 1 1 1 0 1 0 1 0 1 0 0 1 1 0}$$

<br><br><br><br><br><br>

#### (3)
Convert the same binary number to hexadecimal. It is provided again for your convenience. Show your work. $$\texttt{0 1 0 1 1 1 0 0 1 0 1 1 1 0 1 0 1 0 1 0 0 1 1 0}$$
<br><br><br><br><br><br><br><br>



### Decimal to Binary Conversion
#### (4)
Convert $248_{10}$ to binary using the systematic method (repeated division). Show your work.

<br><br><br><br><br><br><br><br><br><br>

#### (5)
Convert $248_{10}$ to binary using the nonsystematic method (powers of 2). Show your work.

<br><br><br><br><br><br><br><br><br><br>

<p style="page-break-after: always;">&nbsp;</p>

#### (6)
Convert $248_{10}$ to hexadecimal *directly* using the systematic method (repeated division). Show your work.

<br><br><br><br><br><br><br><br><br><br>

#### (7)
Convert $248_{10}$ from binary to hexadecimal using the conversion table. Isn't this easier?

<br><br><br><br><br><br><br>

#### (8)
Convert $248_{10}$ from binary to octal using the conversion table.

<br><br><br><br><br><br><br>

<p style="page-break-after: always;">&nbsp;</p>

### Challenges
#### C1
Below is a conversion table for base 64,[^1] which uses essentially every character found on a standard keyboard. It is useful for encoding images into text, which is common on the internet and for email attachments.

![[Base 64 Conversion Table.png]]

Convert the following binary number into base 64. Show your work. $$\small\texttt{000011100010100000100010101101011010100101001011101000100000100010011100}$$

<br><br><br><br><br><br><br><br>

[^1]: https://en.wikipedia.org/wiki/Base64

#### C2
Convert the following number to base $4$ using the nonsystematic method, but with powers of $4$ instead of powers of $2$. Show your work. $$3\,044\,998\,776_{10}$$

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>