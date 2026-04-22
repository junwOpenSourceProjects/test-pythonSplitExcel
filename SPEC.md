# SPEC.md - 项目规格说明书

## 1. 项目概述

- **项目名称**: test-pythonSplitExcel
- **项目类型**: Python 脚本项目
- **项目描述**: Excel 文件拆分工具，支持按行数、按列值、按工作表等多种方式拆分 Excel 文件。

## 2. 技术栈

- Python 3.8+
- Pandas 2.x
- OpenPyXL 3.x

## 3. 项目结构

```
test-pythonSplitExcel/
├── pythonBase/             # Python 基础代码目录
├── README.md               # 项目说明
├── LICENSE                 # 许可证
└── .gitignore              # Git 忽略配置
```

## 4. 核心功能

- 按行数拆分 Excel 文件
- 按列值拆分 Excel 文件
- 按工作表拆分 Excel 文件
- 自定义拆分条件
- 批量处理

## 5. 验证运行

项目为 Python 脚本项目，无需编译，直接运行 python 脚本即可。

## 6. Git 状态

- 仓库状态: clean
- 分支: main