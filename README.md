# gitlab-ci
git自动生成tag版本号之CI配置

目标：每次合并master自动给本次需求打tag，生成tag版本分支。参考.gitlab-ci.yml配置。

代码合并入master时自动触发gitlab ci自动化打tag
tag版本号自动从项目对应的配置文件中获取，自动触发yml配置文件执行

文章链接：https://juejin.cn/post/6912290828677939214/

