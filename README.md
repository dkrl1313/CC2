# CC2

151002

error가 났다...

[hadoop@localhost ~]$ hadoop fs -ls /
Java HotSpot(TM) Client VM warning: You have loaded library /home/hadoop/hadoop-2.7.1/lib/native/libhadoop.so.1.0.0 which might have disabled stack guard. The VM will try to fix the stack guard now.
It's highly recommended that you fix the library with 'execstack -c <libfile>', or link it with '-z noexecstack'.
15/10/02 00:11:23 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
Found 3 items
drwxr-xr-x   - hadoop supergroup          0 2015-10-01 23:42 /output
drwx------   - hadoop supergroup          0 2015-10-01 23:25 /tmp
drwxr-xr-x   - hadoop supergroup          0 2015-10-01 23:25 /user
[hadoop@localhost ~]$ hadoop fs -ls /output
Java HotSpot(TM) Client VM warning: You have loaded library /home/hadoop/hadoop-2.7.1/lib/native/libhadoop.so.1.0.0 which might have disabled stack guard. The VM will try to fix the stack guard now.
It's highly recommended that you fix the library with 'execstack -c <libfile>', or link it with '-z noexecstack'.
15/10/02 00:11:27 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
[hadoop@localhost ~]$ hdfs dfs -cat /output/part-r-00000
Java HotSpot(TM) Client VM warning: You have loaded library /home/hadoop/hadoop-2.7.1/lib/native/libhadoop.so.1.0.0 which might have disabled stack guard. The VM will try to fix the stack guard now.
It's highly recommended that you fix the library with 'execstack -c <libfile>', or link it with '-z noexecstack'.
15/10/02 00:11:32 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
cat: `/output/part-r-00000': No such file or directory

