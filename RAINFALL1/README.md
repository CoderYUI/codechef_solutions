# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/RAINFALL1](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/RAINFALL1)

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
		
		while (t-- > 0){
		    int x = sc.nextInt();
		    if (x<3) System.out.println("LIGHT");
		    else if (x>=3  && x<7) System.out.println("MODERATE");
		    else System.out.println("HEAVY");
		}

	}
}
```
