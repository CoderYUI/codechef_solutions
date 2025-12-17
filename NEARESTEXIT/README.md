# Problem

**Problem URL:** [http://codechef.com/practice/course/logical-problems/DIFF800/problems/NEARESTEXIT](http://codechef.com/practice/course/logical-problems/DIFF800/problems/NEARESTEXIT)

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
		    if (x>50) System.out.println("RIGHT");
		    else System.out.println("LEFT");
		}

	}
}
```
