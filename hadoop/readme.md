environment 一栏下面是配置一些环境变量的([参考](https://hub.docker.com/r/uhopper/hadoop))

- 例如需要在 `core-site.xml` 配置 `fs.defaultFS` 的属性

```$xslt
CORE_CONF_fs_defaultFS=hdfs://namenode:8020
```

- 在 `yarn-site.xml` 设置 `yarn.log-aggregation-enable` 属性

```$xslt
YARN_CONF_yarn_log___aggregation___enable=true
```

常用端口号

https://blog.csdn.net/baiBenny/article/details/53887328
