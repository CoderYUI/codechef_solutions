# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/F1RULE](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/F1RULE)

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
		Scanner input = new Scanner(System.in);
		int t = input.nextInt();
		
		while(t-- > 0){
		    int x = input.nextInt();
		    int y = input.nextInt();
		    double limit = ((double) x * 107) / 100;
		    if (limit>= y) System.out.println("YEs");
		    else System.out.println("No");
		}

	}
}
```
