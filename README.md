# 前言

欢迎来到我们的基于微信小程序的医院体检管理系统项目！本项目旨在为医院提供便捷、高效的体检管理服务，同时为患者提供更好的体检预约和使用体验。以下是关于本项目的详细介绍。

## 内容介绍

本项目采用前后端分离的设计模式，后端基于SSM框架（Spring、SpringMVC、MyBatis）进行开发，前端使用微信小程序技术，同时结合Vue、JS和CSS3等前端技术，实现了一套功能完善、易于扩展的医院体检管理系统。主要功能包括：体检套餐管理、体检预约、体检报告查询等。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis，微信小程序
- 前端技术：JS、Vue、CSS3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何使用MyBatis实现体检套餐的查询功能：

```java
// MyBatis Mapper接口
public interface ExamPackageMapper {
    @Select("SELECT * FROM exam_package WHERE id = #{id}")
    ExamPackage getExamPackageById(@Param("id") int id);
}

// Service层调用
public ExamPackage getExamPackageById(int id) {
    return examPackageMapper.getExamPackageById(id);
}

// Controller层调用
@RequestMapping("/getExamPackageById")
@ResponseBody
public ExamPackage getExamPackageById(int id) {
    return examPackageService.getExamPackageById(id);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/346506/13/2946/149873/68c5a371Fd2a39aa1/642ab1c4ab998321.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/344312/12/3093/13690/68c5a348Fdbb1d804/06655ec915679747.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349890/26/3096/12965/68c5a348F2ff9752b/0a01c85562c7819f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/341463/27/2782/23932/68c5a349Fda496ee9/fda50a02394dcf9a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338051/28/10551/21933/68c5a349F47c51439/7853c48e25b09e24.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348195/34/3103/19660/68c5a349F16f522a2/9863df927f93390d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/348738/11/2964/21832/68c5a34aF75d4b532/a96bdfae01b6b929.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349621/34/3012/37752/68c5a34aF54df0b82/25a40bba75872381.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/323375/34/19864/33186/68c5a34aF0daa5b00/9867e1be240a2b8c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325969/37/19822/18241/68c5a34aF081c9f64/ca0fa69f042ddb93.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
