# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PRACTICEPERF](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PRACTICEPERF)

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
		int p1 = sc.nextInt();
		int p2 = sc.nextInt();
		int p3 = sc.nextInt();
		int p4 = sc.nextInt();
		
		int count = 0;
		
		if (p1>=10) count++;
	    if (p2>=10) count++;
	    if (p3>=10) count++;
	    if (p4>=10) count++;
	    
	    System.out.println(count);

	}
}
```
