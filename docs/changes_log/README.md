# 更新日志

> 框架的更新以发版的形式进行记录，你同样可以在 [Github](https://github.com/wu-clan/httpfpt/releases)
> 查看变更记录

## v0.1.0a1 (2023-06-11)
- 添加基于 github 的ci工作流
- 添加更多 typing 提示基于 ruff 规则
- Bump requests from 2.25.1 to 2.31.0
- 💥 重命名项目名为 httpfpt

## v0.0.6a1 (2023-04-25)

- 更新使用文档至 [httpfpt_docs](https://wu-clan.github.io/httpfpt/)
- 修复测试报告电子邮件附件乱码
- 增加测试数据架构验证
- 更新基于 black 的测试用例自动生成器
- 增加 ruff 支持
- 增加 pre-commit 支持
- 增加 black 支持

## v0.0.5a3 (2023-03-28)

- 更新json断言类型 `not contains` 为 `not_contains`
- 更新日志控制台输出的默认状态为关闭
- 添加 pytest 运行参数控制台打印
- 删除所有对 excel 作为用例数据文件的支持
- 修复用例数据模式模型部分的参数类型，注意它目前没有被定义为非常严格的
- 添加 pydantic 数据验证，目前是可选的
- 修复解析某些可归零参数时缺乏条件判断的问题

## v0.0.5a2 (2023-03-24)

- 增加用例唯一 ID 检测和重复 ID 坐标捕获输出
- 更新请求数据解析规则
- 增加引擎内置 raise_for_status 方法，提前触发请求异常
- 修复头文件类型自动解析没有更新到请求数据的问题
- 升级 pytest==7.2.2，并设置最低版本为 >= 7.0.0

## v0.0.5a1 (2023-03-20)

第一个预览版本
