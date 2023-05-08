Download Link: https://assignmentchef.com/product/solved-programming-challenge-2
<br>
5/5 - (1 vote)

The colors red, blue, and yellow are known as the primary colors because they cannot be made by mixing other colors.



When you mix two primary colors, you get a secondary color, as shown here: When you mix red and blue, you get purple When you mix red and yellow, you get orange When you mix blue and yellow, you get green

Your challenge is to write a class called ColorMix.java and TestColorMix.java.

ColorMix.java accepts three Strings: color1, color2, color3.

The program must return to the user the colors entered, the result of mixing the colors e.g. purple, orange, or green. The class must also tell the user if no color mix is found and if the user entered similar colors.

The ColorMix.java must include the following:

1. Final constants: String BLUE = “blue”; String RED = “red”; String GREEN =”green” (3 points)

2. Instant variables String color1, String color2 (2 points)

3. Constructs (10 points each) public ColorMix() public ColorMix(String col1, String col2)

4. Mutators (5 points) public void setColor1 (String col1) public void setColor2 (String col2)

5. Accessors (5 points) public String getColor1 () public String getColor2 ()

6. A method public String mixColor() . The method uses if statements in conjunction with logical operators (&amp;&amp;, ||, == and != ) to prints the outcome of mixing the colors. The outcome includes 5 results: purple, orange, green, entered similar colors, no color combination possible. (35 points)

Here are some hints:

if (color1.compareTo(color2)==0) System.out.print(“entered same colors”);

if (((color1.compareTo(RED) == 0) &amp;&amp; (color2.compareTo(BLUE) ==0 )) || ((color1.compareTo(BLUE) == 0) &amp;&amp; (color2.compareTo(RED) == 0))) System.out.print(“Color Purple”);

The test program TestColorMix.java must print the following (10 points)

1. A short description of the purpose of the program

2. Ask the user to enter two colors to mix

3. Colors entered by user