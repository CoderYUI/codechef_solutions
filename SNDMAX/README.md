# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/SNDMAX](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/SNDMAX)

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
		
		while(t-->0){
		    int n = sc.nextInt();
		    int nTwo = sc.nextInt();
		    int nThree = sc.nextInt();
		    if (n>nTwo && n>nThree){
		        if (nTwo>nThree){
		            System.out.println(nTwo);
		        }else System.out.println(nThree);
		    }else if (nTwo > n && nTwo> nThree){
		        if (n > nThree) System.out.println(n);
		        else System.out.println(nThree);
		    }else if (nThree> n && nThree> nTwo) {
		        if (n>nTwo) System.out.println(n);
		        else System.out.println(nTwo);
		    }else System.out.println(n);
		}

	}
}
```
