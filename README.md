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


2.
import java.util.*;
public class acad{
public static void main(String[] args){
Scanner sc=new Scanner(System.in);
int a=sc.nextInt();   //number from user
for(int i=1;i<=10;i++)
{
System.out.println(a+"x"+i+"="+(a*i));  //displays 1st 10 multiples of a
}
}
}


3.
import java.util.*;
public class acad{
public static void main(String[] args){
Scanner sc=new Scanner(System.in);
int a=sc.nextInt();   //1st number from user
int b=sc.nextInt();   //2nd number from user
int c=sc.nextInt();   //3rd number from user
sum(a,b);
sum(a,b,c);
}
//method overloading
public static void sum(int a,int b)
{
System.out.println("Sum of first 2 numbers is:"+(a+b));
}
public static void sum(int a,int b,int c)
{
System.out.println("Sum of all 3 numbers is:"+(a+b+c));
}
}
