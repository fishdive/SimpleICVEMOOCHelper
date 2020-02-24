# SimpleIcveMoocHelper

## 一个简单基于油猴+jquery 开发实现的智慧职教MOOC,职教云网课助手

- 支持自动评论

- 自动阅览 PPT 和视频

- 自动在讨论区抓取有效讨论内容,参与讨论

- 自动解除作业复制限制 (1.06 added)

- 提供窗口用于提取题库 (1.07 added)

- 暂不支持答题功能(无题库支撑)

- 已支持绿版职教云,zjy2(ver 2.0 added)

- 增加自定义选项openMultiplyComment用于是否启用评论选项卡下多项评论功能(ver 2.08 added)

- 细分各评论开关选项(优先级低于自定义全项)(ver 2.09 added)

- 兼容内含文件夹的课件(ver 2.10 added)

- 兼容文件和图文课件(ver 2.101 added)

- 插件上架[油猴](https://greasyfork.org/zh-CN/scripts/396813-%E6%99%BA%E6%85%A7%E8%81%8C%E6%95%99%E8%81%8C%E6%95%99%E4%BA%91-%E7%BD%91%E8%AF%BE%E5%8A%A9%E6%89%8B-%E7%BB%BF%E7%89%88),已支持一键安装,追踪更新
  
- ........

---

> 如果觉得有所帮助,请给我一个[star](https://github.com/W-ChihC/SimpleIcveMoocHelper),谢谢
> 
> 又或者在页面最下方扫码赏臭不要脸的一根辣条钱☕️,[捐赠者名单❤️](捐赠者名单.md)
>
>
> 如有问题欢迎issue

---

油猴插件简单说明: 在浏览器插件中心(扩展中心啥啥的)搜索关键字 **tampermonkey** 等待安装完成

本插件使用说明: 油猴安装完成后找到 **添加新脚本** 选项后,将本脚本全选复制进编辑框,按快捷键 Ctrl+S 即可食用

注意:本脚本需在点击具体小节后才会运行,运行前有 10 秒等待时间,运行流程可按 F12 查看

---

|            |                                               |                                                              |
| ---------- | --------------------------------------------- | ------------------------------------------------------------ |
| Mooc版本   | MOOC学院? [蓝版](https://mooc.icve.com.cn/profile.html) | 职教云? [绿版](https://zjy2.icve.com.cn)                             |
| 测试浏览器 | Chrome                                        | Chrome                                                       |
| 已知问题   | 暂无                                          | ~~无法获知当前课程是否完成~~,无法获知PPT是否完成(iframe跨域),疑网站反作弊升级或教师设置,无法正常显示评论区,但评论功能正常运作               |
| 源文件     | bule.src.js                                   | green.src.js                                                 |
| 版本       | 1.07                                          | 2.10 (因网站实现方式,基于blue1.07大幅度修改,大部分功能改用异步处理) |

~~大一菜鸡 学习 JS 练手所写, ES5,6 瞎混搭,勿喷~~

已经大二了

ver.1.0 完成时间 : 2019.5.25

ver.2.0 完成时间 : 2019.12.13

> 优化思路：改用阻塞队列处理任务，解决因应对定时器搭配异步处理不太稳定导致时间较长的问题

![支付宝](alipay.jpg?raw=true)![微信支付](wechat.png?raw=true)

---

### **本插件仅供个人学习研究和交流使用，请于下载后二十四小时内删除,勿要滥用,用于商业用途等**

> 如作它用所承受的法律责任一概与作者无关（各种途径使用即代表你同意上述观点)
