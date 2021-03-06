# struct、union、enum、typedef
---
1. 结构是数据对象的组合：
<pre>
    struct struct_name
    {
        lists;
    };    
</pre>
2. 声明结构时一定不要忘记添加分号！！！
3. 结构定义： `struct struct_name name;`
4. 可以将声明与定义合在一起，这时可以省略结构名：
<pre>
    struct struct_name
    {
        lists;
    }name;  
</pre>
5. 结构初始化：
    * 使用一个花括号括起来的、逗号分隔的初始化项目列表进行初始化；
    * 每个初始化项目必须和要初始化的结构成员类型相匹配；
6. 静态结构初始化时，所有成员必须使用常量表达式；
7. 初始化指定项目：
<pre>
struct struct_name name = { .list0 = 1, .list3 = 2};
</pre>    
8. 允许把一个结构赋给另一个结构；
9. 如果用结构存储字符串，成员一定要使用字符数组（对C来说），字符串指针没有初始化，会出现问题；
10. 联合是一个能在同一个存储空间里（但不同时）存储不同类型数据的数据类型,记得加分号：
<pre>
    union union_name name
    {
       lists;
    };
</pre>
11. 编译器分配足够大的空间以保存联合所描述的可能性的最大需要；
12. 使用枚举类型声明代表整数常量的符号名称，使用关键字`enum`声明；
13. C允许对枚举变量使用增量运算符，但C++不允许；
14. 枚举列表的常量默认被指定为0,1,2,...;
15. C使用术语名字空间(namespace)来表示识别一个名字的程序部分；
    * 名字相同，作用域不同的两个变量不会冲突；
    * 同一作用域的标记（如函数名）与变量在C中可以使用同一个名字，但在C++不行，C++将变量和标记放在同一个名字空间中；
16. typedef，使你能够为某一类型创建自己的名字；
    * typedef给出的符号名称仅限于对类型；
    * typedef的解释由编译器执行；#define由预处理器执行；        
