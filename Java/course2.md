

####  Java程序基础

#####  Java程序基本结构

> 对一个简单的Java程序的解析

```java
/**
* 可以用来自动创建文档的注释
*/
public class Hello {
    	public static void main(String[] args){
            //向屏幕输出文本：
            System.out.println("Hello,world!")；
            /* 多行注释开始
            注释内容
        	注释结束 */
        }
}//class定义结束
```

> 各模块的基本解析
>
> > + 类名需以英文字母开头，后接字母，数字和下划线的组合
> > + 驼峰命名
> > + `public`是修饰限定符,表示该类公开，不写`public`也可正常编译，但是这个类无法从命令行执行
> > + `class`内部可以定义若干方法（method），方法名命名和class一样，但首字母小写，其余采用驼峰命名

```java
public class Tsst{//类名是Test
    public static void main(String[] args){  //方法名是main
        //方法代码
    }//方法定义结束
}//class定义结束
```

#####  变量

```java
public class Main {
    public static void main(String[] args) {
        int n = 100; // 定义变量n，同时赋值为100
        System.out.println("n = " + n); // 打印n的值

        n = 200; // 变量n赋值为200
        System.out.println("n = " + n); // 打印n的值

        int x = n; // 变量x赋值为n（n的值为200，因此赋值后x的值也是200）
        System.out.println("x = " + x); // 打印x的值

        x = x + 100; // 变量x赋值为x+100（x的值为200，因此赋值后x的值是200+100=300）
        System.out.println("x = " + x); // 打印x的值
        System.out.println("n = " + n); // 再次打印n的值，n应该是200还是300？
   }
}
```

> 变量的类型
>
> >整数：`byte` `short` `int` `long` 
> >
> >浮点数：`float` `double`
> >
> >字符型：`char`
> >
> >布尔型：`boolean`
>
> 注意点：
>
> >计算机的最小储存单位是byte，一个字节是一个8位二进制数，即8个bit。
> >
> >一字节为1byte，1024字节是1M，1024M是1G，1024G是1T
> >
> >