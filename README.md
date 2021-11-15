# 《深入理解Java代码审计》

本项目是记录自己在学习Java代码审计过程中遇到的优秀内容，包括Java代码审计技巧以及优秀的Java代码审计案例。一个不会Java代码审计的师傅不是一个好黑客，一个不会Java代码审计的黑客不是一个好师傅！深入理解Java代码审计，手握众多重点Java应用高危0day！作者：[0e0w](https://github.com/0e0w/HackJava)

本项目创建于2021年7月8日，最近的一次更新时间为2021年11月15日。本项目会持续更新，直到海枯石烂。

- [01-Java代码审计资源](https://github.com/0e0w/HackJava#01-java%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E8%B5%84%E6%BA%90)
- [02-Java代码审计工具](https://github.com/0e0w/HackJava#02-java%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E5%B7%A5%E5%85%B7)
- [03-Java漏洞靶场平台](https://github.com/0e0w/HackJava#03-java%E6%BC%8F%E6%B4%9E%E9%9D%B6%E5%9C%BA%E5%B9%B3%E5%8F%B0)
- [04-Java安全Web漏洞](https://github.com/0e0w/HackJava#04-java%E5%AE%89%E5%85%A8web%E6%BC%8F%E6%B4%9E)
- [05-Java代码审计实战](https://github.com/0e0w/HackJava#05-java%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E5%AE%9E%E6%88%98)
- [06-Java安全编码规范](https://github.com/0e0w/HackJava#06-java%E5%AE%89%E5%85%A8%E7%BC%96%E7%A0%81%E8%A7%84%E8%8C%83)
- [08-Java代码审计老师](https://github.com/0e0w/HackJava#07-java%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E8%80%81%E5%B8%88)

## 01-Java代码审计资源

一、书籍资料
- [ ] [《Java代码审计 入门篇》](https://item.jd.com/10033832360716.html)@陈俊杰等
- [ ] [《Java代码审计实战》](https://item.jd.com/13466996.html)@高昌盛等
- [ ] [《Java-Web-Security》]()@Dominik Schadow

二、基础教程
- [ ] [《Java Web安全-代码审计》]()@凌天实验室
- [ ] [《Java安全漫谈笔记相关内容》](https://github.com/phith0n/JavaThings)@phith0n
- [ ] [《Java代码审计学习笔记》](https://github.com/proudwind/javasec_study)@proudwind
- [ ] [《Java漏洞学习笔记》](https://github.com/SummerSec/JavaLearnVulnerability)@SummerSec
- [ ] [《代码审计入门小项目》](https://github.com/cn-panda/JavaCodeAudit)@cn-panda
- [ ] [《自学Java安全总结》](https://github.com/Maskhe/javasec)@Maskhe
- [ ] [《攻击Java Web应用》](https://github.com/March110/javaweb-sec)@安百科技
- [ ] [《Java RCE 回显测试代码》](https://github.com/feihong-cs/Java-Rce-Echo)@feihong
- [ ] [《Java反序列化技术分享》](https://github.com/Y4er/WebLogic-Shiro-shell)@Y4er
- [ ] [《Java代码审计总结》](https://github.com/huyuanzhi2/CodeReview)@huyuanzhi2
- [ ] [《代码审计知识点整理-Java》](https://github.com/7hang/--Java)@7hang
- [ ] [《Java代码审计案例》](https://github.com/5huai/POC-Test)@5huai
- [ ] [《java安全和java框架漏洞》](https://github.com/Firebasky/Java)@Firebasky
- [ ] [《Java安全相关的漏洞和技术demo》](https://github.com/threedr3am/learnjavabug)@threedr3am
- [ ] [《跟我一起JAVA代码审计》](https://www.freebuf.com/column/1289)@0neOfU4

三、视频教程
- [ ] [《MS08067安全实验室》](https://space.bilibili.com/396298765?spm_id_from=333.788.b_765f7570696e666f.2)@MS08067
- [ ] [《Java代码审计系列课程》](https://edu.51cto.com/course/27875.html)@Hack_Man

四、培训演讲

五、审计报告

六、其他资源
- [ ] [《攻击Java Web应用》](https://zhishihezi.net/b/5d644b6f81cbc9e40460fe7eea3c7925)@javasec
- [ ] [《J2EE 渗透测试与安全开发》](https://zhishihezi.net/b/98ae566719b21536dff0c4febaa697d2)@路人甲
- [ ] [《静态程序分析入门教程》](https://github.com/RangerNJU/Static-Program-Analysis-Book)
- [ ] https://github.com/su18/JDBC-Attack
- [ ] https://xz.aliyun.com/t/7945

## 02-Java代码审计工具

工欲善其事必先利其器，此处收集整理Java代码审计的一些优秀工具！期待自己的代码审计工具能够早日发布！

一、Frotify
- [ ] https://github.com/wooyunwang/Fortify

二、IDEA
- [ ] https://github.com/XianYanTechnology/RocB
- [ ] https://github.com/momosecurity/momo-code-sec-inspector-java

三、JNDI工具
- [ ] https://github.com/su18/JNDI
- [ ] https://github.com/welk1n/JNDI-Injection-Exploit
- [ ] https://github.com/feihong-cs/JNDIExploit
- [ ] https://github.com/welk1n/JNDI-Injection-Exploit

四、反序列化工具
- [ ] https://github.com/wh1t3p1g/ysomap
- [ ] https://github.com/frohoff/ysoserial
- [ ] https://github.com/KpLi0rn/ysoserial
- [ ] https://github.com/0range228/Gadgets
- [ ] https://github.com/ikkisoft/SerialKiller
- [ ] https://github.com/5wimming/gadgetinspector
- [ ] https://github.com/threedr3am/gadgetinspector
- [ ] https://github.com/JackOfMostTrades/gadgetinspector

五、文件监控类工具
- [ ] https://github.com/TheKingOfDuck/MySQLMonitor

六、其他工具
- [ ] https://github.com/HXSecurity/DongTai
- [ ] https://github.com/MobSF/mobsfscan
- [ ] https://github.com/threedr3am/log-agent
- [ ] https://github.com/wh1t3p1g/tabby
- [ ] https://github.com/EmYiQing/XVulnFinder
- [ ] https://github.com/EmYiQing/CodeInspector
- [ ] https://github.com/mtxiaowangzi/CAFJE
- [ ] https://github.com/FeeiCN/Cobra
- [ ] https://github.com/returntocorp/semgrep

## 03-Java漏洞靶场平台

- [ ] [WebBug-JavaEE编写的Web漏洞靶场](https://github.com/Mysticbinary/WebBug)@mysticbinary
- [ ] [JavaSecurity-Java Web漏洞演示程序](https://github.com/dschadow/JavaSecurity)@dschadow
- [ ] [Java-Web-Security-书籍完整代码示例](https://github.com/dschadow/Java-Web-Security)@dschadow
- [ ] [maobugs-Java 漏洞平台包含各种CVE演示](https://github.com/langligelang/maobugs)@langligelang
- [ ] [SecExample-Java漏洞靶场](https://github.com/tangxiaofeng7/SecExample)@tangxiaofeng7
- [ ] [java sec code-学习Java漏洞代码的项目](https://github.com/JoyChou93/java-sec-code)@JoyChou93
- [ ] [dvja-该死的易受攻击的 Java EE应用程序](https://github.com/appsecco/dvja)@appsecco
- [ ] [JavaVulnerableLab-易受攻击的Java Web应用程序](https://github.com/CSPF-Founder/JavaVulnerableLab)@CSPF-Founder
- [ ] [Java_deserialize_vuln_lab-Java反序列化学习的实验代码](https://github.com/bit4woo/Java_deserialize_vuln_lab)@bit4woo
- [ ] [Java-EE-VulnWeb用于演示的Java Web漏洞项目](https://github.com/mtxiaowangzi/Java-EE-VulnWeb)@mtxiaowangzi
- [ ] [Hello Java Sec-Java安全编码和代码审计](https://github.com/j3ers3/Hello-Java-Sec)@3ers3
- [ ] [javaweb codereview-演示java代码审计程序](https://github.com/iiiusky/javaweb-codereview)@iiiusky
- [ ] [sqlilab Jsp-jsp版sqlilab 1-21关](https://github.com/yhy0/sqlilab-Jsp)@yhy0
- [ ] [ShiroAndFastJson-shiro加fastjson环境](https://github.com/safe6Sec/ShiroAndFastJson)@safe6Sec
- [ ] [mytestvul-一个用来做漏洞复现/验证的小框架](https://github.com/novysodope/mytestvul)@novysodope
- [ ] [JavaVulnerableLab circle-练习Java反序列化的最简单环境](https://github.com/pmiaowu/DeserializationTest)@pmiaowu
- [ ] [易受攻击的Java Web应用程序](https://github.com/Zhangyao-zzyy/JavaVulnerableLab-circle)@Zhangyao-zzyy
- [ ] https://github.com/t0thkr1s/allsafe
- [ ] https://github.com/oversecured/ovaa
- [ ] https://github.com/jaiswalakshansh/Vuldroid

## 04-Java安全Web漏洞

本部分详细列举常见的Java安全漏洞内容。

- 程序安装问题
- 业务逻辑漏洞
- SQL注入漏洞
- 变量覆盖漏洞
- 任意文件上传漏洞
- 任意文件写入漏洞
- 任意文件删除漏洞
- 任意文件包含漏洞
- 任意命令执行漏洞
- Java反序列化漏洞
- XSS漏洞
- XXE漏洞
- CSRF漏洞
- SSRF漏洞

## 05-Java代码审计实战

## 06-Java安全编码规范

- 腾讯-Java安全编码规范
- 绿盟-Java安全编码规范
- [陌陌-Java安全编码规范](https://github.com/momosecurity/rhizobia_J)
- 华为-Java安全编码规范
- 奇安信-Java安全编码规范
- 软通动力-Java-Web安全开发规范

## 07-Java代码审计老师

本人在学习Java代码审计的过程中遇到了很多优秀的Java代码审计工程师，感谢这些研究者！

- 待更新

[![Stargazers over time](https://starchart.cc//0e0w/HackJava.svg)](https://starchart.cc/0e0w/HackJava)