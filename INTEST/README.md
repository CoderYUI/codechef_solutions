# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/INTEST](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/INTEST)

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
		
		int  n = sc.nextInt();
		int k = sc.nextInt();
		int count = 0;
		
		while (n>0){
		    int numbers = sc.nextInt();
		    if ((numbers%k)==0){
		        count++;
		    }
		    n--;
		}
		System.out.println(count);
		
	}
}
```
