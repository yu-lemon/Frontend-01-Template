# 每周总结
## unicode

Unicode CJK
即中文 日文 韩文取值范围

用查出ascii范围内的字符，会导致编码出现问题

\u转义
String.codeUnicode

语义组成：
InputElement 
   WhiteSpace
   LineTerminator
   Comment
   Token(javascript 中一些有效的东西都叫token)
     Punctuator
     IndetifierName
       Keywords
       Indetifier
       Future reserved Keywords（将来要用的关键）:enum
    Literal
       Number
       String
       Boolean

## Number
IEEE 754 Double Float 
>* Sign(1) 符号位
>* Exponent(11)
>* Fraction (52)
### Grammar
>* DecimalLiteral
>* BinaryLiteral
>* OctalIntegerLiteral
>* HexIntegerLiteral


## String
>* character
>* Code Point
>* Encoding
#
写一个正则表达式 匹配所有 Number 直接量
写一个 UTF-8 Encoding 的函数
写一个正则表达式，匹配所有的字符串直接量，单引号和双引号


## 作业 本周赶需求，没有留下充足时间来学习和完成作业  后期会努力赶上

   LineTerminator加班
   LineTerminator干需求
   LineTerminator
