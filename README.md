主要原理就是在这个jar包中设置公钥到系统环境变量中，为了安全，将这个类加密，这个类会在jvm启动的时候解密

编译过程

mvn clean install 后

得到jar包 lk-ss-1.6.jar

执行A的main方法类

在target/classes下有看到D.classen，将D.classen替换lk-ss-1.6.jar中的D.class