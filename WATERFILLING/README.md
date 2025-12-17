# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/WATERFILLING?tab=statement](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/WATERFILLING?tab=statement)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		
		int t = sc.nextInt();
		int arr[] = new int[3];
  		
		while (t-- > 0){
		    arr[0] = sc.nextInt();
		    arr[1] = sc.nextInt();
		    arr[2] = sc.nextInt();
		    
		    int notFilled = 0;
		    for (int nums : arr){
		        if (nums ==0) notFilled++;
		    }
		    if (notFilled>=2) System.out.println("WATER FILLING TIME");
		    else System.out.println("NOT NOW");
		    
		    
 		    
		}

	}
}


/*


import java.util.Scanner;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner in = new Scanner(System.in);
		int T = in.nextInt(); //for No. of test cases
		while(T-->0) {
		    //your code goes here
		    int b1 = in.nextInt(); //Status of bottle 1
		    int b2 = in.nextInt(); //Status of bottle 2
		    int b3 = in.nextInt(); //Status of bottle 3
		    System.out.println((b1+b2+b3)<2?"Water filling time":"Not now");
		}
		in.close();
	}
}*/
```
