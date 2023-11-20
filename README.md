# ConfigurationEnvironment
配置库

1.下载github加速器

https://gitee.com/rmbgame/SteamTools/releases/download/3.0.0-rc.2/Steam%20%20_v3.0.0-rc.2_win_x64.exe

2.下载git

https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.2/Git-2.42.0.2-64-bit.exe

2.1配置ssh公钥

https://blog.csdn.net/qq_36667170/article/details/79094257


3.下载2023idea

https://download.jetbrains.com.cn/idea/ideaIU-2023.2.5.exe

4.下载jdk

4.1下载jdk19

https://download.oracle.com/java/19/archive/jdk-19.0.2_windows-x64_bin.exe

4.2下载jdk8

https://download.oracle.com/otn/java/jdk/8u381-b09/8c876547113c4e4aab3c868e9e0ec572/jdk-8u381-windows-x64.exe?AuthParam=1700371837_243c071d5303b6fa3405bf2e65a93c60

4.3配置Java系统环境变量

{

  1.新建系统变量：JAVA_HOME
路径取jdk路径
E:\xxx\jdk1.8


  2.在系统变量Path后面追加
%JAVA_HOME%\bin
%JAVA_HOME%\jre\bin
3. 添加classpath


  CLASSPATH


  .;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar


4. 验证



C:\Users\frank>javac -version
javac 1.8.0_241

}



5.tomcat下载

https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.83/bin/apache-tomcat-9.0.83-windows-x64.zip

6.maven下载

https://dlcdn.apache.org/maven/maven-3/3.9.5/binaries/apache-maven-3.9.5-bin.zip

