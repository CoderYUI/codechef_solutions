# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/MONOPOLY?tab=solution](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/MONOPOLY?tab=solution)

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
		    int z = sc.nextInt();
		    
		    if (x > (y+z)) System.out.println("yes");
		    else if (y > (x +z )) System.out.println("yes");
		    else if (z > (x+y)) System.out.println("yes");
		    else System.out.println("no");
		    
		}

	}
}
```
