# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/M1ENROL](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/M1ENROL)

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
		    int y = sc.nextInt();
		    
		    if (x<y) System.out.println((Math.max(x,y))-(Math.min(x,y)));
		    else System.out.println("0");
		    
		    
		}

	}
}
```
