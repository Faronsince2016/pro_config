# py
## 基本环境
### 基本组件

- python 3.5

### 环境部署组件

- virtualenv ()

## 部署步骤
- 建立虚拟环境

```sh
进入terminal(Pycharm添加terminal方案：https://blog.csdn.net/YZXnuaa/article/details/79310498) 
virtualenv --python=python3 --prompt='(env)' .env # 安装虚拟环境
source .env/bin/activate # 激活虚拟环境
```

- 安装依赖

```sh
#方案1（翻墙）
pip install -i https://pypi.doubanio.com/simple/ -r requirements.txt
#方案2（不用翻墙）
pip install -r requirements.txt
```



- 项目启动

```sh

```



