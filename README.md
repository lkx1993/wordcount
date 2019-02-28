wordcount
=========

Hadoop MapReduce word counting with Java

Run with:

    hadoop jar wordcount.jar "input_folder" "output_folder"

"input_folder" and "output_folder" are folders on HDFS.

执行命令:
hdfs dfs -mkdir -p /test/in
hadoop jar /opt/wordcount.jar com.jordiburgos.WordCount /test/in /test/out  

hadoop hdfs dfs基本操作https://blog.csdn.net/wild46cat/article/details/68939094

//顺便吐槽一句如果是360或搜狗浏览器的话，commit 按钮是永远都无法点击的，囧。。
