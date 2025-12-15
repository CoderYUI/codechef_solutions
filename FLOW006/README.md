# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/FLOW006](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/FLOW006)

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
		    int n = sc.nextInt();
		    int sum = 0;
		
		    while (n>0){
		        int a = n%10;
		        sum+=a;
		        n = n/10;
		    }
		    System.out.println(sum);
		}
		
		
	}
}
```
