# Todo List Application

这是一个使用 Flask 和 MySQL 建立的待办事项 (Todo List) Web 应用。

## 功能

- 添加待办事项
- 按日期查看待办事项
- 更新待办事项
- 删除待办事项

## 安装

这个项目使用 [Python 3](https://www.python.org/download/releases/3.0/) 和 [MySQL](https://www.mysql.com/). 请确保你本地安装了它们。

首先克隆仓库到你的本地：

```sh
$ git clone https://github.com/yourgithubusername/todolist.git
$ cd todolist
```

然后安装所有需要的依赖：

使用 pip:

```sh
$ pip install -r requirements.txt
```

或者使用 pipenv:

```sh
$ pipenv install
```

你需要建立一个 MySQL 数据库，并修改 `app.py` 文件中的数据库URI，以连接到你的数据库。

## 使用说明

你可以通过运行以下命令来启动应用：

```sh
$ python app.py
```

在浏览器中访问 `http://localhost:5000` 可以打开应用。

## 贡献

对于 bug 报告或者增加新特性，请查看贡献指南。

## 许可证

本项目使用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解更多详情。
```

