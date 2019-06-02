学习hadoop的时候，为了让那个不太会用java语言但是对sql很熟悉的工程师能够操作基本的mapreduce计算过长，hive就被设计出来了。

UDF定义
--
User-Defined Function

把我们写好的UDF放到Hive中去使用
--
首先我们将用java写好的UDF函数编译后的Java类打包成为一个JAR文件，并在Hive中注册这个文件（相当于告诉Hive这个是我写的UDF）
