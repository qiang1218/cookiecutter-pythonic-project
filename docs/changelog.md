# 变更记录

## v0.4.0

### 2022-08-23

- 使用 [poetry](https://python-poetry.org/) 管理虚拟环境和打包发布，弃用 pipenv 。
- 移除索引服务器配置
- 移除 `python 3.7` 和 `python 3.8` 支持。推荐使用 `python 3.10` 。
- 更新相关依赖包到最新版本
- 更新 gh action 版本
- 更新 gitlab-ci 的发布逻辑
- 更新文档

## V0.3.0

### 2021-10-20

- 特性 py39 py310 支持
- 特性 [PEP 585](https://www.python.org/dev/peps/pep-0585/) 支持。对于版本小于 3.9 的代码增加 `from __future__ import annotations` 导入
- 特性 增加 pytest-xdist ，并启用并行化测试。
- 文档 更新 README 和使用文档。

### 2021-08-31

- 修复部署连接错误
- 修复 README.md 代码检测错误

### 2021-06-16

- 增加文档
- 增加文档部署相关操作

### 2021-06-04

- 修复配置模块中的注释错误
- 修复生成的项目名中有空格
- 修复 github-action 中依赖任务名称错误
- 修复 .gitignore 文件没有最条件匹配

### 2021-01-21

- 完善项目模板

## V0.2.0

### 2021-1-19

- 初始化项目