# j--
参考书籍：Introduction to Compiler Construction in a Java World Source 

###jminusminus为源码主目录，其结构为
* Scanner.java 词法器,没有跟踪上一个Token的功能
* LookaheadScanner.java 在Scanner 的基础上，利用vector和stack容器提供跟踪前面扫过的Token的功能
* Parser.java 递归下降的解析器，利用了LookaheadScanner。

* 

