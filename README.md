# prep4

package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int rows=sc.nextInt();
	System.out.println("enter no of coloumns");
	int coloumns=sc.nextInt();
	for (int i=0;i<=rows;i++)
	{
	  for(int k=1;k<=(rows-i);k++)
	  {
	     System.out.print(" ");
	  }
	  for( int j=1;j<=i;j++)
	  {
	System.out.print("*");
   }
	  System.out.println();
  }
 }
}

enter no of rows
5
enter no of coloumns
5
     
    *
   **
  ***
 ****
*****



package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int rows=sc.nextInt();
	System.out.println("enter no of coloumns");
	int coloumns=sc.nextInt();
	for (int i=0;i<=rows;i++)
	{
	  for(int k=1;k<=(rows-i);k++)
	  {
	     System.out.print(" ");
	  }
	  for( int j=1;j<=i;j++)
	  {
	System.out.print("* ");
   }
	  System.out.println();
  }
 }
}

enter no of rows
5
enter no of coloumns
5
     
    * 
   * * 
  * * * 
 * * * * 
* * * * * 


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	int mid=(n+1)/2;
	for (int i=1;i<=mid;i++)
	{
	  for(int k=1;k<=(mid-i);k++)
	  {
	     System.out.print(" ");
	  }
	  for( int j=1;j<=(2*i-1);j++)
	  {
	 System.out.print("*");
     }
	  System.out.println();
     }
	 for (int i=1;i<=(mid-1);i++)
		{
		for (int k=1;k<=i;k++)
		{
			System.out.print(" ");
		}
        for(int j=1;j<=2*(mid-i)-1;j++)
        {
			System.out.print("*");
        }
        System.out.println();
	}
  }
 }

enter no of rows
9
    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *
    

package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
		for(int k=1;k<=i-1;k++)
		{
			System.out.print(" ");
			}
	    for( int j=1;j<=n-(i-1);j++)
	    {
	    System.out.print("*");
         }
	  System.out.println();
     }
	}
 }

 enter no of rows
5
*****
 ****
  ***
   **
    *


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
		for(int k=1;k<=i-1;k++)
		{
			System.out.print(" ");
			}
	    for( int j=1;j<=n-(i-1);j++)
	    {
	    System.out.print("* ");
         }
	  System.out.println();
     }
	}
 }

enter no of rows
5
* * * * * 
 * * * * 
  * * * 
   * * 
    * 


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
	    for( int j=1;j<=i;j++)
	    {
	    System.out.print("*");
         }
	  System.out.println();
     }
	for (int i=1;i<=n-1;i++)
	{
      for( int j=1;j<=n-i;j++)
	    {
	    System.out.print("*");
         }
	  System.out.println();
	}
	}
 }

enter no of rows
8
*
**
***
****
*****
******
*******
********
*******
******
*****
****
***
**
*


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
		for (int k=1;k<=n-i;k++)
		{
			System.out.print(" ");
		}
	    for( int j=1;j<=i;j++)
	    {
	    System.out.print("*");
         }
	  System.out.println();
     }
	for (int i=1;i<=n-1;i++)
	{
		for(int k=1;k<=i;k++)
		{
			System.out.print(" ");
		}
      for( int j=1;j<=n-i;j++)
	    {
	    System.out.print("*");
         }
	  System.out.println();
	}
	}
 }

 enter no of rows
10
         *
        **
       ***
      ****
     *****
    ******
   *******
  ********
 *********
**********
 *********
  ********
   *******
    ******
     *****
      ****
       ***
        **
         *


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
		for (int k=1;k<=i-1;k++)
		{
			System.out.print(" ");
		}
	    for( int j=1;j<=n-(i-1);j++)
	    {
	    System.out.print("* ");
         }
	  System.out.println();
     }
	for (int i=1;i<=n-1;i++)
	{
		for(int k=1;k<=n-i;k++)
		{
			System.out.print(" ");
		}
      for( int j=1;j<=i;j++)
	    {
	    System.out.print("* ");
         }
	  System.out.println();
	}
	}
 }
enter no of rows
10
* * * * * * * * * * 
 * * * * * * * * * 
  * * * * * * * * 
   * * * * * * * 
    * * * * * * 
     * * * * * 
      * * * * 
       * * * 
        * * 
         * 
         * 
        * * 
       * * * 
      * * * * 
     * * * * * 
    * * * * * * 
   * * * * * * * 
  * * * * * * * * 
 * * * * * * * * * 




