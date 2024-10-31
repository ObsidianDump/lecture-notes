Conditional statements break the flow of code allowing for branching programs.
## Examples
if else statements
```java
int x = 0;

if(x > 0){
System.out.println("x is larger then 0");
}
else if(x == 0){
System.out.println("x is equal to 0");
}
else{
System.out.println("x is less then 0");
}

```
 [[Shorthand]] if else statement:
```java
int x = 0;

String result = (x > 0) ? "x is larger then 0" : "x is less then zero";
System.out.println(result);
```
Switch statements:
```java
int x = 0;

switch (x):{
	case 1:
		System.out.println("one");
		break;
	case 2:
		System.out.println("two");
		break;
	case 3:
		System.out.println("three");
		break;
	default:
		System.out.println("Unknown");
}

```