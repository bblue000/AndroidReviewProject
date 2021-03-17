### 选择题

**1、`System.out.println("5" + 2);`的输出结果应该是（&nbsp;&nbsp;&nbsp;&nbsp;）**

A、52

B、7

C、2

D、5

**2、 0.6332的数据类型是（&nbsp;&nbsp;&nbsp;&nbsp;）**

A、float

B、double

C、Float

D、Double

**3、 下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**
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

**4、 下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**

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

**5、下列程序运行的结果是（&nbsp;&nbsp;&nbsp;&nbsp;）**

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

### SQL题

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

1）用一条SQL语句查询出每门课程获得最高分的学生姓名和分数
```










```

### Java编程题和逻辑算法题

**1、完成下面的类，实现你认为最安全的单例模式。**

```Java
public class Singleton {






















}
```

**2、反转链表**

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

