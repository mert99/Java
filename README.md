搭建J2EE环境
===============
- 下载JDK
- 设置环境变量
    
    e.g. 在~/.bashrc添加下面几行
    `# Set the Java Environment Variables`
    `export JAVA_HOME="$HOME/J2EE/jdk1.7.0_07"`
    `export PATH="$JAVA_HOME/bin:$PATH"`
    `export CLASSPATH=".:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar"`
- 下载Tomcat
