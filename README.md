# study_python
python学习


**pip**<br/>
```
sudo apt-get install python-pip
```

**virtualenv**<br/>
```
sudo pip install virtualenv
```
***使用方法***
```
virtualenv ENV  #创建一个名为ENV的目录, 并且安装了ENV/bin/python, 创建了lib,include,bin目录,安装了pip
cd ENV
source ./bin/activate  #激活当前virtualenv
#使用pip查看当前库
pip list
#关闭virtualenv
deactivate
```
