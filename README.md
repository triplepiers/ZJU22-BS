# ZJU22-BS

> 虽然丢人，但是还是开个源吧
> 图标拖动部分其实有很大bug，但是懒得修了orz

## 1 实验目的

任选 Web 开发技术实现一个用于智能家居设备管理的系统

## 2 实验要求

需要实现的基本功能如下：
1. 实现用户注册、登录功能，用户注册时需要填写必要的信息并验证，如：

    - 用户名、密码要求在6字节以上
    - 手机号的格式验证
    - 用户名和手机号在系统中唯一

2. 用户登录后可以创建场所，然后在场所里创建智能设备
    
    （中间可以加一级，就是场所里先创建房间，然后在房间里创建智能设备）

3. 设备类型至少支持以下几种

    - 灯（支持 开关 && 亮度调节）
    - 开关
    - 传感器（温湿度灯信息查看）
    - 门锁（开关门状态上报）

4. 提供列表信息查看设备信息、设备状态和上报信息

5. 提供可视化界面展示以上信息，可以在房间户型图（上传图片）上摆放设备，
    或者提供画图功能画出场所图
6. 可以在手机上查看，手机应用可以是网页，也可以是App

为方便提交作业，项目数据库建议使用 MySQL 或 hsqldb，提交作业时附带建表脚本。

## 3 文档要求 & 评分标准

- 独立完成
- 要求界面友好、提供必要的文档（包括 设计文档 和 使用手册 等其他文档）

- 《设计文档》于 11.7 前提交，占 20% 最终总评成绩。
    
    打包上传学在浙大 或 发送至 ______

- 1.1 前提交 程序代码 和 实验报告。文档包括：

    - 实验报告封面
    - 设计文档
    - 其他文档（如使用手册、测试报告、开发体会、小结等）
    源代码文件

> Final DDL后因某些原因延迟至 1.12
