# 毕设做的Django任务平台网页  


## 使用教程:  

### 1.安装django与python环境  

#### 1.1安装 Python  

访问 https://www.python.org/downloads/ 下载最新版本的 Python 并安装。
在安装过程中，勾选“Add Python x.x to PATH”选项，让 Python 在命令行中全局可用。  

#### 1.2安装 Django  

打开命令行（Windows 中使用 PowerShell 或 cmd，Mac 和 Linux 使用终端）。
使用 pip 工具安装 Django。运行以下命令：  

```pip install django```
#### 1.3安装MYSQL  

下载 MySQL 安装程序：前往 MySQL 官方网站（https://dev.mysql.com/downloads/mysql/）下载适用于你的操作系统的 MySQL 安装程序。  
运行安装程序：双击下载的安装程序并按照安装向导的指示进行操作。在安装过程中，你可以选择安装类型、安装位置和其他选项。
### 2.启动 Django 项目
进入到刚刚创建的项目目录：  

```cd web```

运行以下命令启动开发服务器：  

```python manage.py runserver 8000```

在浏览器中访问 http://127.0.0.1:8000/ ，如果看到 Django 的欢迎页面，则说明项目已成功启动。  
