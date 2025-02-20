# 更新日志

## v3.5.1.1

2021-09-26

- 【修复】修复上个版本，xml文件无法自定义目录的问题
- 【变动】实体类，开启lombok注解，@Data变更为@Getter和@Setter
- 【优化】重写MyAutoGenerator，与之前版本不兼容
- 【优化】优化boolean处理
- 【升级】mysql-plus-generator -> 3.5.1
- 【升级】mysql-plus -> 3.4.3.4
- 【升级】mysql8 -> 8.0.26
- 【升级】mysql5 -> 5.1.49
- 【升级】spring-boot -> 2.5.5


## v3.5.0.3

- 【修复】修复关闭字段注解无效的问题。([#13](https://github.com/fengwenyi/mybatis-plus-code-generator/issues/13))
- 【新增】服务docker化。([#12](https://github.com/fengwenyi/mybatis-plus-code-generator/issues/12))
- 【升级】spring-boot 2.5.4
- 【升级】api-spring-boot-starter 1.0.1

## v3.5.0.2

- 【新增】新增忽略字段，继承父类的字段不再生成
- 【修复】修复开启swagger支持报错问题([#9](https://github.com/fengwenyi/mybatis-plus-code-generator/issues/9))
- 【修复】修复开启lombok却不生效的问题([#10](https://github.com/fengwenyi/mybatis-plus-code-generator/issues/10))

## v3.5.0.1

- mybatis-plus-generator版本升级到3.5.0
- 生成器的代码重构，MyAutoGenerator
- 更新阿里云Maven仓库地址
- 引入 api-spring-boot-starter 依赖
- 删除 CommonUtils
- 删除全局异常处理，由 api-spring-boot-starter 处理
- 删除业务异常(BizException)，改为 api-spring-boot-starter 的 ApiException
- 新增debug日志打印

## v3.4.1-3

- 实体类支持lombok配置 #6
- 实体类支持数据库字段配置 #7
- XML自定义配置 #8

## 2021.07.27

- 优化提供的默认值。
- 修复说明文档运行命令不正确的问题。
- 调整数据库信息输入的顺序。
- 数据库密码输入框改为明文。
- 优化说明文档。

## 2021.07.26

- 提供更多配置。
- 优化界面。
- 加入banner。

## 2021.07.13

- 通过UI界面录入数据库参数生成代码。