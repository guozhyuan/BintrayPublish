##### 1. 导入bintray.gradlew到工程,复制gradlew.properties&local.properties中的属性到工程对应文件

##### 2. 工程根build.gradle 添加依赖
	classpath 'com.github.dcendents:android-maven-gradle-plugin:2.0'
	classpath 'com.jfrog.bintray.gradle:gradle-bintray-plugin:1.7.3'

##### 3.库build.gradle中底部添加apply from: "../bintray.gradle" <依据bintray.gralde文件的相对位置>