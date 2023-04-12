
#java

All Exceptions come from class Throwable
There are 2 types of statements:
1. Normal Statements - `int i = 1;`
2. Critical statements - `int k = 1/j;`
```mermaid
graph TD
%% Top Node
id1(Throwable)
id1.1(Exception - Can be Handeled)
id1.2(Error - Cannot be Handeled)

id2.1(Checked Exceptions)
id2.2(Unchecked Exceptions)

id1--> id1.1 & id1.2
id1.1-->id2.2
id1.1-->id2.1
```

```java
try {
	int i = j/k;
}
catch(ArithmaticException ae) {
	// some code
}
```
