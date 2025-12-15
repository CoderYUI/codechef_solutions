# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/AIRLINES](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/AIRLINES)

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
		
		while (t-- >0){
		    int x = sc.nextInt() * 10;
		    int y = sc.nextInt();
		    int z = sc.nextInt();
		    
		    if (x>=y) System.out.println(y*z);
		    else System.out.println(x*z);
		}

	}
}
```
