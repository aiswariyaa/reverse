# reverse
import java.io.*;
import java.util.scanner;
class reverse string
{
public static void main(string args[])
{
String s1;
String r1;
Scanner in=new Scanner(System.in);
System.out.println("enter the original string:")
s1=in.nextline();
int k=s1.length();
for(int i=k-1;k>=0;k--)
r1=r1+s1.charAt(i);
System.out.println("the reversed string:"+r1)
}
} 
