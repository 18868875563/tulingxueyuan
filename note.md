#Django系统
- 环境
    - python3.6
    - django1.8
- 参考资料
    - django中文教程 usyiyi.cn
    - django架站的16堂课
#环境搭建
- anaconda+pycharm
- anaconda使用
    - conda list：显示当前环境安装的包
    - conda env list：显示安装的虚拟环境列表
    - conda create -n env_name python=3.6 
    - 激活conda的虚拟环境
        - source activate env_name
        - conda activate env_name
    - pip insatll django=1.8
#后台需要的流程

#创建第一个django程序
- django-admin startproject tulingxueyuan
- 启动cd到对应目录下
python manage.py runserver
- pycharm启动
    -需要启动
    
# 路由系统-urls
- 创建app
    - app：负责一定具体业务或者一类具体业务的模块
    - python manage.py startapp teacher
- 路由
    - 按照具体的请求url，导入到对应的业务处理模块的一个功能
    - django的信息控制中枢
    - 本质上是接受的URL和相应的处理模块的一个映射
    - 在接受URL请求的匹配上使用RE（正则）
    - URL的具体格式入urls.py中所示  