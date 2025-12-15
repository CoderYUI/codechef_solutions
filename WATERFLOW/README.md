# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/WATERFLOW](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/WATERFLOW)

## Solution

```java

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner i = new Scanner(System.in);
		int t = i.nextInt();
		
		while (t-- > 0){
		    int w = i.nextInt();
		    int x = i.nextInt();
		    int y = i.nextInt();
		    int z = i.nextInt();
		    
		    if (((y*z)+w)>x) System.out.println("overflow");
		    else if (((y*z)+w)==x) System.out.println("filled");
		    else System.out.println("Unfilled");
		}

	}
}
```
