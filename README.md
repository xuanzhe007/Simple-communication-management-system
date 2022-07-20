# Simple-communication-management-system
very simple project


## 通讯录管理系统：

#### 1、系统需求

通讯录是一共可以记录亲人，好友信息的工具。

主要利用c++来实现一共通讯录管理系统

系统中需要实现的功能如下：

添加联系人、显示联系人、删除联系人、查找联系人、修改联系人、清空联系人、退出通讯录。

#### 2、创建项目

使用vs

#### 3、菜单功能

功能描述：用户选择功能的界面。

封装函数showMenu

#### 4、退出功能

功能描述：退出通讯录系统

思路：根据用户不同的选择，进入不同的功能，可以选择switch分支结构。当用户选择0时候，执行退出。

#### 5、添加联系人

功能描述：实现添加联系人功能，联系人上限为1000人，联系人信息包括（姓名、性别、年龄、联系电话、家庭住址）

思路：设计联系人结构体，设计通讯录结构体，main函数中创建通讯录，封装添加联系人函数addPerson。

#### 6、显示联系人

功能描述：显示通讯录已有的联系人信息

思路：封装显示联系人函数showPerson

判断如果当前通讯录中共没有人员，就提示记录为空，人数大于01，显示通讯录中信息。

#### 7、删除联系人

功能描述：按照姓名进行删除指定联系人

思路：封装检查联系人是否存在的函数isExist 、封装删除联系人函数。

检测联系人是否存在，如果存在，返回联系人在通讯录中的位置，不存在返回-1。

#### 8、查找联系人

功能描述：按照姓名查看指定联系人信息

思路：封装查找联系人函数selectPerson

判断用户指定的联系人是否存在，如果存在显示信息，不存在则提示查无此人。

#### 9、修改联系人

功能描述：按照姓名重新修改指定联系人

思路：封装修改联系人函数

查找用户输入的联系人，如果查找成功进行修改操作，查找失败提示查无此人。

#### 10、清空联系人

功能描述：清空通讯录中所有信息

思路：封装清空联系人函数

只要将通讯录记录的联系人数量置为0，做逻辑清空即可。
