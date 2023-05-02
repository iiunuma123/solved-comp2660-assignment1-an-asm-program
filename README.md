Download Link: https://assignmentchef.com/product/solved-comp2660-assignment1-an-asm-program
<br>
Write an ASM program that evaluates the following expression, using variables:

<h1>EDX = (A + B) – (C + D)</h1>

Declare and initialize the memory variables <em>A, B, C, </em>and<em> D</em> to 32-bit signed integer values -10, +210, -3456, +43210, respectively. Register EDX contains the result.

<ol>

 <li>Display the string “<em>EDX = </em>(<em>A + B</em>)<em> – </em>(<em>C + D</em>)” alone in a single line.</li>

 <li>Display the values of all the variables together in the next line; each separated by 3 spaces and a dash and 3 spaces again.</li>

 <li>Display an empty line</li>

 <li>Display the result <em>EDX</em>, in binary, then in decimal, and then in hexadecimal; each in a separate line.</li>

</ol>

<strong>Question  #2</strong> (10 points)

Write an ASM program that uses the variable below and MOV instructions to copy the value from <strong>bigEndian</strong> to <strong>littleEndian</strong>, reversing the order of the bytes. The number’s 32bit value is understood to be 12345678h.

.data bigEndian  BYTE 12h, 34h, 56h, 78h littleEndian DWORD ?

Display the values of <strong>bigEndian</strong> and <strong>littleEndian</strong>.