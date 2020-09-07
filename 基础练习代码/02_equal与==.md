`equal`判断值是否相同，而`==`判断是否是同一个对象
# 代码演示1
```java
package test;


public class MyRandom {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Integer a = new Integer(10);
		Integer b = new Integer(10);
		if(a==b) {
			System.out.println("相等");
		}else {
			System.out.println("不相等");
		}
	}

}
```
# 测试结果1
    不相等
# 代码演示2
```java
package test;

public class MyRandom {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Integer a = new Integer(10);
		Integer b = new Integer(10);
		if(a.equals(b)) {
			System.out.println("相等");
		}else {
			System.out.println("不相等");
		}
	}

}
```
# 测试结果2
    相等
