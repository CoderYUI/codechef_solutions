# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SUGARCANE](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SUGARCANE)

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
		while(t-- > 0){
		    int n = sc.nextInt();
		    
		    int totalcoins = n*50;
		    System.out.println(totalcoins - ((7*totalcoins)/10));
		    
		    
		}
		

	}
}
```
