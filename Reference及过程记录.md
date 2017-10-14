# References

## Database & Backend
@ssh ​ ​@zhm

* [http://www.jianshu.com/p/dce8a7fab69d](http://www.jianshu.com/p/dce8a7fab69d)
* 一个和我们的项目需求很像的例子：[https://github.com/dockersamples/atsea-sample-shop-app](https://github.com/dockersamples/atsea-sample-shop-app)

## React ​& js(es6)
@wsc ​ ​@muzi ​ ​@wenj

* [http://wiki.jikexueyuan.com/project/es6/intro.html](http://wiki.jikexueyuan.com/project/es6/intro.html)
* [https://reactjs.org/](https://reactjs.org/)

## UI ​ ​Design
转战​[https://modao.cc](https://modao.cc)

* 管理员界面（仅编辑）：[https://modao.cc/app/6JfTmllHZj2t53FM0o9gVch861b5J9t](https://modao.cc/app/6JfTmllHZj2t53FM0o9gVch861b5J9t)
* 用户界面（仅编辑）：[https://modao.cc/app/P1VzR7q1cH8hs7DgPt7JIBDtIC5j6It](https://modao.cc/app/P1VzR7q1cH8hs7DgPt7JIBDtIC5j6It)

# 系统设计
Server Code Structure

![架构图](架构图.png)

## configuration
spring boot权限等的基本配置

## security
信息安全性的配置


## admin
### controller
1. LoginController:提供管理员登录API
2. CompetitionListController:提供比赛列表相关API
3. CompetitionController:提供比赛详细信息API
### service
2. LoginService:用户登录相关
1. CompetitionListService:比赛列表相关（简化的比赛信息）
2. CompetitionController:比赛细节相关
### model
提供admin的数据类型
### repositories
封装与数据库交互API


## client
### controller
1. LoginController:提供用户登录API
2. OrderController:提供订单相关API
3. TradeController:提供双方交易API
3. ConfigController:提供队伍的财产信息和基本信息API
### service
1. CompetitionService:比赛相关
2. LoginService:用户登录相关
2. OrderService:订单相关
### model
提供admin的数据类型
### repositories
封装与数据库交互API


# 项目进度
## Sprint1
### 时间
9.28-10.12（第二周到第四周）
### 任务
完成初步的Demo原型，验证关键技术
### 实际时间线
* 10.5：基本画完了管理员界面
* 10.11：确定了一套REST API，但是还可能需要修改；见文件中的REST API.pdf（参照[https://github.com/dockersamples/atsea-sample-shop-app/blob/master/REST.md](https://github.com/dockersamples/atsea-sample-shop-app/blob/master/REST.md)）
* 10.12：开会，发现另一组已经什么都做完了，和用户讨论了一下界面的问题。用户界面还缺一些东西没有做，管理员界面可能需要重新设计。@wj  助教建议我们赶紧做完，这样可以让用户实际测试一下，最后的得分可能会比较高。

## Sprint2
### 时间
10.12-10.26（第四周到第六周）
### 任务
功能分解，团队分工。
开始版本控制和代码风格检查。
### 实际时间线

## Sprint3
### 时间
10.26-11.9（第六周到第八周）
### 任务
单元测试
### 实际时间线

## Sprint4
### 时间
11.9-11.23（第八周到第十周）
### 任务
明确系统部署要求。
### 实际时间线

## Sprint5
### 时间
11.23-12.2（第十周到第十一周）
### 任务
明确系统测试、项目文档要求。
### 实际时间线

## 过程及原型系统功能评价
### 时间
12.2（11周1）
### 任务
过程及原型系统功能评价。

## 检查系统测试、项目文档。明确课堂演示要求
### 时间
12.21（14周4）
### 任务
检查系统测试、项目文档。明确课堂演示要求。

## 大作业课堂展示
### 时间
12.28（15周1）
### 任务
大作业课堂展示

## 截止日期
### 时间
1.15（18周1）
### 任务
所有大作业交付截止。最终评价。
