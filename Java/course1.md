#### Java主类结构
```java
public class First {
    static String s1 = "你好";
    public static void main(String[] args){
    String s2= "Java";
    System.out.println(s1);
    System.out.println(s2);
    }
}
```
> Java结构
>
> + 主类名与文件名一致，类名首字母大写
>
> + class(类)，`class`用来定义一个类，`public`表示这个类是公开的，类名后的  第一个花括号`{}`为类的定义
>
> + 在定义当中，我们定义了一个`main`的方法
>
>   ```java
>   public static void main(String[] args){
>       ...
>   }
>   ```
>
>   方法是可执行的代码块，除了`main`方法名外还有`()`括起来的方法参数，这里的`main`方法只有一个参数，类型为`String[]`，参数名是`args`，`public`,`static`用来修饰方法，这里表示这是一个公开的静态方法，`void`是方法返回类型
>
> + `javac`可以将一个`.java`文件，编译成`.class`文件
>
> + `java`可以运行一个已编译的Java文件，参数是类名。
>

