# 前言

欢迎来到本项目的仓库！这是一个以微信小程序为前端，SSM（Spring、SpringMVC、MyBatis）框架为后端的作品集展示项目。本项目旨在帮助大家更好地了解和掌握微信小程序与SSM框架的开发技术。以下是关于本项目的详细介绍。

# 内容介绍

本项目是一个作品集展示微信小程序，主要功能包括作品展示、分类查看、搜索、评论等。后端采用SSM框架进行开发，实现了用户管理、作品管理、评论管理等功能。前端则采用微信小程序进行展示，界面简洁、美观，提供了良好的用户体验。

# 技术介绍

## 语言：Java

## 使用框架：
- Spring
- Spring MVC
- MyBatis
- 微信小程序

## 前端技术：
- JS
- Vue
- CSS3
- Uniapp

## 开发工具：
- IDEA/Eclipse
- Uniapp

## 数据库：
- MySQL 5.7/8.0

## 数据库管理工具：
- phpstudy/Navicat

## JDK版本：
- jdk1.8

## Maven：
- apache-maven 3.8.1-bin

## 前端环境：
- Node.Js 12\14\16

# 核心代码

以下是本项目中的一个核心代码片段，展示了如何使用Spring MVC处理前端请求：

```java
@RestController
@RequestMapping("/api/works")
public class WorksController {

    @Autowired
    private WorksService worksService;

    @GetMapping("/list")
    public ResponseEntity<List<Works>> listWorks(@RequestParam("categoryId") Integer categoryId) {
        List<Works> worksList = worksService.listWorks(categoryId);
        return ResponseEntity.ok(worksList);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/328935/29/19429/105536/68c57104F4d030702/f4e8acee53a4ca60.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/350008/38/2985/33476/68c570dcFe2ca3304/1767f1d156f8d173.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327873/11/19669/23199/68c570dcFa9450033/e97c2cf42ee3e316.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327459/32/19702/19467/68c570ddF1132c700/2a579cf2dabec620.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336819/24/10512/22472/68c570ddF1b82c1d4/37303fdc5303f477.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/342846/21/2881/17739/68c570ddF2ad3a2e2/af2e036ed6aa56c0.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/329397/33/12867/14391/68c570ddF5ba91f3d/ef986204aa318645.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344830/13/3013/18030/68c570ddF9374623c/1ff214f401b50d41.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325588/30/19667/20971/68c570deFb7e68b8d/3555c8316985b3e4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336032/24/10609/16740/68c570deF472f0749/c86d38fdab96cb75.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
