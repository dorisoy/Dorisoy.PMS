# Dorisoy.PMS

早期一款用于团队项目任务进度安排和协作的管理系统,系统采用使用.Net.Mvc开发，数据库使用MYSQL，你可以使用它来便捷管理你的项目计划任务和活动安排，并且将任务分配给项目团队成员来完成缺陷和开发的工作内容， 监控项目团队成员任务进度，系统支持多项目，多团队成员分配协做和权限管理，提供预览，邮件提醒，日历视图，进度表，归档存储以及任务评论。

# 项目结构

    Dorisoy.PMS.sln
    |-- DB
    |-- Dorisoy.PMS
    |   |-- Add_Data
    |   |   |-- project
    |   |-- App_Start
    |   |-- Areas
    |   |   |-- Admin
    |   |   |   |-- Controllers
    |   |   |   |-- Views
    |   |   |       |-- Calendar
    |   |   |       |-- Login
    |   |   |       |-- Notification
    |   |   |       |-- Progress
    |   |   |       |-- ProjectDetail
    |   |   |       |-- Projects
    |   |   |       |-- Shared
    |   |   |       |-- SignUp
    |   |   |       |-- ToDoLists
    |   |   |       |-- UpComingEvents
    |   |   |-- SuperAdmin
    |   |       |-- Controllers
    |   |       |-- Views
    |   |           |-- AdminDetail
    |   |           |-- Login
    |   |           |-- Shared
    |   |-- Content
    |   |-- Images
    |   |-- Models
    |   |-- Scripts
    |   |   |-- images
    |   |-- Upload
    |   |   |-- ProjectAttachment
    |   |-- Utility_Class
    |   |   |-- Controllers
    |   |-- Views
    |       |-- Account
    |       |-- Calendar
    |       |-- Login
    |       |-- Nav
    |       |-- Notification
    |       |-- Progress
    |       |-- ProjectDetail
    |       |-- Registeration
    |       |-- Shared
    |       |-- SignUp
    |       |-- ToDoLists
    |       |-- UpComingEvents
    |-- PagedList
    |-- PagedList.Mvc


# 功能

## 仪表板

统计项目、任务、错误和成员的总数。任务概述和项目状态的可视化表示可以帮助您估计每个任务的进度，您可以检查到期任务。

## 多项目

创建多个不同的项目，您可以创建单个项目或授予对邀请其他用户的项目的访问权限。您还可以让其他用户成为项目管理员

## 项目管理

通过让您轻松记录启动、计划项目任务和活动以及将任务分配给项目团队成员来启动任何项目 监控项目团队成员如何以及何时执行分配的任务 显示所有项目任务的当前状态（分配/取消分配, Completed /InCompleted) 和每项任务的负责人

## 项目工具

在仪表板中查看所有项目详细信息。显示任务和错误的总数以及项目中完成的数量。显示分配给他们项目的开发人员的数量。

## 由管理员添加新项目

单击添加新项目按钮创建一个新项目。在此处添加项目详细信息，例如项目名称、项目图标、描述，并添加一个或多个项目团队成员电子邮件。创建项目以邀请项目负责人或项目成员。

## 项目任务状态定义

待办事项，分配待办事项，取消分配待办事项，已完成的待办事项，未完成的待办事项，任务待办事项，错误待办事项，完成待办事项
过滤项目任务和缺陷作为优先级（优先级分为High、Medium和Low三种）。
待办事项：由项目管理员、项目组长在任务列表中添加待办事项 有两种类型的待办事项： 1： 任务 2： 分配给项目团队或开发人员的 Bug 待办事项。设置任务的高、中和低优先级以及分配任务的日期，以防止向分配的开发人员发送带有附件和文档的评论
分配待办事项：显示分配给团队成员或开发人员的待办事项列表
未分配待办事项 ：显示创建的未分配给项目团队成员或任何其他开发人员的待办事项列表。
已完成的待办事项列表：显示开发者已完成的已完成任务详情 任务完成后由分配的开发者更新待办事项状态
未完成的待办事项列表 : 显示分配给开发者的列表。
缺陷待办事项 : 显示项目的所有 Bugs 列表，状态为 Assigned、Unassigned、Completed 和 Incompleted
完成待办事项： 显示所有完成待办事项列表，当一个项目任务或bug被创建并分配给开发人员时，由开发人员在他们更新待办事项系统中的完成待办事项状态后完成。

## 文件附件

每个项目都有其文档或其他文件附件，如流程图、流程等……这里创建的项目具有附加和存储与该项目相关的一些文档的设施。

## 日历视图

它为项目规划提供了日历视图的最佳工具之一。日历按天、周、月和年提供计划任务的高级视图。拥有可共享的任务和时间管理日历，项目管理员不仅可以查看一个团队的项目计划，还可以查看其他团队的项目计划。

## 进度

在进度报告中定义的项目中发生了什么。

## 已归档项目

显示已归档的所有项目。


# 截图 

<img src="https://github.com/dorisoy/Dorisoy.PMS/blob/main/s%20(1).png"/>
<img src="https://github.com/dorisoy/Dorisoy.PMS/blob/main/s%20(5).png"/>
<img src="https://github.com/dorisoy/Dorisoy.PMS/blob/main/s%20(4).png"/>
<img src="https://github.com/dorisoy/Dorisoy.PMS/blob/main/s%20(3).png"/>
<img src="https://github.com/dorisoy/Dorisoy.PMS/blob/main/s%20(2).png"/>

