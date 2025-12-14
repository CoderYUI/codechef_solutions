# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/MVR](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/MVR)

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
		int arr[] = new int[4];
		arr[0] = sc.nextInt();
		arr[1] = sc.nextInt();
		arr[2] = sc.nextInt();
		arr[3] = sc.nextInt();
		
		if ((arr[0]*2 + arr[1])>(arr[2]*2+arr[3])) System.out.println("Messi");
		else if ((arr[0]*2 + arr[1])==(arr[2]*2+arr[3])) System.out.println("Equal");
		else System.out.println("Ronaldo");

	}
}
```
