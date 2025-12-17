# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/AMR15A](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/AMR15A)

## Solution

```java
public static void main (String[] args) throws java.lang.Exception
{
	Scanner sc = new Scanner(System.in);
	int n = sc.nextInt();
	int cnt = 0;
	for(int i=1; i<=n; i++) {
		int x;
		x = sc.nextInt();
		if( x % 2 == 0 ) {
			cnt ++;
		}
	}
	System.out.println( cnt > n - cnt ? "READY FOR BATTLE" : "NOT READY" );	
}
```
