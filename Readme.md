1. 字符串赋值给rune数组：str:= []rune(str)
2. golang中数组是值类型
3. 切片类型，通过make来创建：make(type([]int), size, capacity(>size))
4. String（）方法可被fmt.Println()使用
5. golang中实现继承的方式：结构体中声明**匿名**结构体字段（父类型）。访问字段或方法时采用就近原则。
6. golang的接口
7. 类型断言：b=a.(String)
8. 空接口interface{}使用
9. testing包做单元测试
10. 遍历管道时，管道需要已经关闭
11. 主函数调用主包内其它函数比较麻烦，最好不要把功能函数放在主包
12. 可以import相对路径
