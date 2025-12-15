# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/HS08TEST](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/HS08TEST)

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
		
		int x = sc.nextInt();
		double y = sc.nextDouble();
		
		if (x%5 == 0 && x<=(y-0.50)) System.out.println(y-x-0.50);
		else System.out.println(y);

	}
}
```
