#### 4.5.1 从哪里断开

自动换行的基本准则是：更倾向于在更高的语法级别处断开。

1.  如果在`非赋值运算符`处断开，那么在该符号前断开(比如+，它将位于下一行)。注意：这一点与Google其它语言的编程风格不同(如C++和JavaScript)。 这条规则也适用于以下“类运算符”符号：点分隔符(.)，类型界限中的&（`<T extends Foo & Bar>`)，catch块中的管道符号(`catch (FooException | BarException e`)
2.  如果在`赋值运算符`处断开，通常的做法是在该符号后断开(比如=，它与前面的内容留在同一行)。这条规则也适用于`foreach`语句中的分号。
3.  方法名或构造函数名与左括号留在同一行。
4.  逗号(,)与其前面的内容留在同一行。

