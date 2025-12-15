# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/ASSIGNMNT](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/ASSIGNMNT)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		
		while (t-- > 0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    int z = sc.nextInt()*1440;
		    
		    if ((x*y)<=z) System.out.println("YES");
		    else System.out.println("NO");
		}
	}
}
```
