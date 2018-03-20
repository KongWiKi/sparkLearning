# Spark学习(目前为Pyspark)

## 1.Spark简单使用

1. 在spark的安装目录中启动pyspark(不知道为什么要最高权限,可能和数据读取有关吧)

2. 可通过设置spark的`conf`目录下的`log4j.properties`文件来管理日志

   ```tex
   log4j.rootCategory = InFO, console 改为
   log4j.rootCategory = WARN, console
   ```

   ​

   减少shell中输出过多的日志信息(`log4j.properties`需要自行创建即复制`conf`中的`log4j.properties.template`并重命名)

3. 简单的行数统计

