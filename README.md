# 前言

在这个特殊的时期，为响应国家疫情防控政策，保障校园师生的健康安全，我们开发了一套基于Spring Boot的校园疫情防控系统。本项目以实用性为出发点，力求为校园疫情防控工作提供便捷、高效的技术支持。

## 内容介绍

本项目主要包括以下功能模块：个人信息管理、健康信息填报、疫情动态展示、防疫知识宣传等。系统采用前后端分离的设计模式，前端负责展示页面及交互，后端负责数据处理与存储。通过本系统，可以实现对校园疫情的实时监控和预警，提高疫情防控工作的针对性和实效性。

## 技术介绍

### 语言：Java
### 使用框架：Spring Boot
### 前端技术：JS、Vue、css3
### 开发工具：IDEA/Eclipse
### 数据库：MySQL 5.7/8.0
### 数据库管理工具：phpstudy/Navicat
### JDK版本：jdk1.8
### Maven: apache-maven 3.8.1-bin
### 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的部分核心代码，以用户健康信息填报为例：

```java
@RestController
@RequestMapping("/health")
public class HealthController {

    @Autowired
    private HealthService healthService;

    @PostMapping("/submit")
    public ResponseEntity<String> submitHealthInfo(@RequestBody HealthInfo healthInfo) {
        boolean result = healthService.saveHealthInfo(healthInfo);
        if (result) {
            return ResponseEntity.ok("提交成功！");
        } else {
            return ResponseEntity.status(HttpStatus.INTERNAL_SERVER_ERROR).body("提交失败，请稍后再试！");
        }
    }
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/310430/2/26454/158896/689df8e8F74f6fd4f/abbc37ddcb3de607.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/293561/2/8060/38036/689df8c9F76a52471/4427c9ddb8ebb29e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/309629/7/26293/92770/689df8caF133e3cdf/8d763efb940e35a6.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327878/5/4634/55655/689df8cbFb980bf80/ecacd317d29406d1.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/295378/36/25954/67305/689df8ccF36ea9c44/f680eae74725772b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311259/13/26638/57994/689df8ccF8e029cce/1fdc1d9b1e1b5bc1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/308215/17/26709/29874/689df8ccF2b5e8e44/65f440b386349df2.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/315199/15/26140/45240/689df8cdF844b145c/d5fd5ecb9d2a7615.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/314742/14/26513/64000/689df8cdF21062712/41a68f0fe429a71b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328381/13/4657/81041/689df8ceF4ba39355/f2f231250c00237b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
