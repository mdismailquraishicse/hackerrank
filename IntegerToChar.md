import java.util.*;

import java.io.*;

public class IntegerToString{

public static void main(String args [])

{

Scanner scan= new Scanner(System.in);

int n=scan.nextInt();

if((n>=-100)&&(n<=100))

{

String s=Integer.toString(n);

System.out.println("Good job");

}

else

System.out.println("Wrong answer");

}

}
