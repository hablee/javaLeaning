random类在`java.util.Random`包中。
# 练习代码
```java
package test;
import java.util.Random;

public class MyRandom {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Random r = new Random();
		for(int i=0;i<3;i++) {
			int a=r.nextInt(100);//左闭右开区间
			System.out.println("生成随机数："+a);
		}
	}

}
```
# 测试结果
    生成随机数：91
    生成随机数：63
    生成随机数：57
