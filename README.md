# Go-Light-Job
A lightweight distributed task scheduling framework implemented with go.（一个用Go编写的轻量级分布式任务调度框架）



## Introduction

## Documentation

## Features

- 1.简单：支持通过Web页面对任务进行CRUD操作，操作简单；

- 2.动态：支持动态修改任务状态、启动/停止任务，以及终止运行中任务，即时生效；

- 3.弹性扩容缩容：一旦有新的worker机器上线或者下线，下次调度时将会重新分配任务；

- 4.触发策略：提供丰富的任务触发策略，包括：Crontab触发、人工触发；

- 5.Rolling实时日志：支持在线查看调度结果，并且支持以Rolling方式实时查看执行器输出的完整的执行日志；

- 6.路由策略：提供丰富的路由策略，包括：广播、群组、随机、指定
