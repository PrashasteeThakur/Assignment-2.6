# Assignment-2.6

import java.util.*;
public class acad{
public static void main(String[] args){
Scanner sc=new Scanner(System.in);
int a=sc.nextInt();   //1st number from user
int b=sc.nextInt();   //2nd number from user
System.out.println("Even numbers are:");
for(int i=a;i<=b;i++)
{
if(i%2==0)       //check if even
{
System.out.println(i);   //displays even numbers
}
}
System.out.println("Odd numbers are:");
for(int i=a;i<=b;i++)
{
if(i%2!=0)      //check if odd
{
System.out.println(i);   //displays odd numbers
}
}
}
}
