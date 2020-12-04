## 候选人姓名：
___

请候选人耐心地答题，尽量多地完成试题，答题时间：30分钟

### Java笔试题

**1、写出你知道的Java中Object类的方法名称：**

```Java




```

**2、写出你知道的Java中String类的方法名称：**

```Java




```

**3、`System.out.println("5" + 2);`的输出结果应该是（&nbsp;&nbsp;&nbsp;&nbsp;）**

A、52

B、7

C、2

D、5

**4、 0.6332的数据类型是（&nbsp;&nbsp;&nbsp;&nbsp;）**

A、float

B、double

C、Float

D、Double

**5、 Java中不通过构造函数也能创建对象吗（&nbsp;&nbsp;&nbsp;&nbsp;）**

A、是

B、否

**6、 下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**
```Java
int i = 2;
System.out.println(i++);
System.out.println(++i);
```
A、3&nbsp;&nbsp;4

B、2&nbsp;&nbsp;3

C、2&nbsp;&nbsp;4

D、3&nbsp;&nbsp;3

E、2&nbsp;&nbsp;2

**7、阅读下面的一段代码**
```Java
class A {
    static {
        System.out.println("1");
    }
    {
        System.out.println("2");
    }
    A() {
        System.out.println("3");
    }
    {
        System.out.println("4");
    }
}
public class Demo {
    public static void main(String[] args) {
        new A();
        new A();
    }
}
```
写出程序运行的打印结果：
```






```

**8、 下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**
```Java
public static void main(String args[]) {
    Thread t = new Thread() {
        public void run() {
            pong();
        }
    };
    t.run();
    System.out.print("ping");
}
    
static void pong() {
    System.out.print("pong");
}
```
A、pingpong

B、pongping

C、pingpong和pongping都有可能

D、都不输出

**9、下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**

```java
public class Example {
    String str = new String("good");
    char[] ch = { 'a', 'b', 'c' };
    
    public static void main(String args[]) {
        Example ex = new Example();
        ex.change(ex.str, ex.ch);
        System.out.print(ex.str + " and ");
        System.out.print(ex.ch);
    }

    public void change(String str, char ch[]) {
        str = "test ok";
        ch[0] = 'g';
    }
}
```
A、 good and abc

B、 good and gbc

C、 test ok and abc

D、 test ok and gbc 

**10、下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**
```java
import java.io.*;
import java.util.*;

public class Foo {
    public static void main (String[] args){
        String s;
        System.out.println("s=" + s);
    }
}
```
A 代码得到编译，并输出“s=”

B 代码得到编译，并输出“s=null”

C 由于String s没有初始化，代码不能编译通过

D 代码得到编译，但捕获到 NullPointException异常


### SQL面试题

**1、有下面一张表**

|name|kecheng|fenshu|
|:--:|:-----:|:----:|
|张三|语文|81|
|张三|数学|75|
|李四|语文|76|
|李四|数学|90|
|王五|语文|81|
|王五|数学|100|
|王五|英语|90|

1）用一条SQL语句查询出所有学生的姓名（最好去重）
```










```

2）用一条SQL语句查询出`语文`课程的最高分数
```










```

3）用一条SQL语句查询出每门课程获得最高分的学生姓名和分数
```










```

4）用一条SQL语句查询出每门课分数都大于80分的学生姓名
```










```

**2、阅读下面的题目，按照要求写出SQL语句：**
```
SQL> SELECT * FROM TEST1;

        ID          F
---------- ----------
         1          A1
         2          A2
         3          A3
         4          A4

SQL> SELECT * FROM TEST2;

        ID          Y
---------- ----------
         3          B1
         4          B2
         5          B3
         6          B4
```

1）我需要得到的结果是：
```
         ID         F             Y
---------- ----------   ----------
         3          A3            B1
         4          A4            B2
```
书写SQL:
```











```

2）我需要得到的结果是：
```
         ID         F             Y
---------- ----------   ----------
         1          A3              
         2          A4              
         5                        B3
         6                        B4
```
书写SQL:
```












```




### Java编程题和逻辑算法题

**1、完成下面的类，实现你认为最安全的单例模式。**

```Java
public class Singleton {






















}
```

**2、甲乙丙丁戊5个人中，有两个人是从不说谎的老实人，另外3位是总是说谎的骗子。下面是他们所说的话:**

甲:乙是骗子

乙:丙是骗子

丙:戊是骗子

丁:甲和乙都是骗子

戊:甲和丁都是老实人

问:谁是老实人?

```










```

**3、请使用冒泡排序对`arr`数组进行排序**

```Java
public class BubbleSort {
    public static void main(String[] args) {
        int[] arr = {95, 23, 34, 11, 75, 56, 78};
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        for (int a = 0; a < arr.length; a++)
            System.out.print(arr[a] + " ");
    }
}
```

**4、反转链表**

```
Input: 1->2->3->4->5->NULL
Output: 5->4->3->2->1->NULL
```

```Java
public class ListNode {
    int val;
    ListNode next;
    ListNode() {}
    ListNode(int val) { this.val = val; }
    ListNode(int val, ListNode next) { this.val = val; this.next = next; }
}
public class Solution {
    public static ListNode reverse(ListNode head) {
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
    }
}
```
