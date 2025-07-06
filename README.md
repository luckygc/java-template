# java-base-template
基线项目，只包含代码样式相关


### ide
插件google-java-format ,选择`aosp`4缩进样式;
插件checkstyle-idea, checkstyle-version版本10.18.2


### 测试
使用junit5加assertj，断言使用assertj


```shell
#验证代码规范
./mvnw.cmd validate
# 格式化
./mvnw.cmd spotless:apply
```
