## 关于BeautyEye
:bulb: BeautyEye工程自2015-01-30日起因众所周知的原因已从 [Google Code](https://code.google.com/p/beautyeye/) 迁移至此。

![](https://code.google.com/p/beautyeye/logo?cct=1376536220)<br>
BeautyEye是一款Java Swing跨平台外观（look and feel）实现；<br>
得益于Android的GUI基础技术，BeautyEye的实现完全不同于其它外观；<br>
BeautyEye是免费的，您可以研究、学习甚至商业用途。

> 迄今为止，BeautyEye没有任何平面设计或相关UI设计人员的参与，仍是纯粹的程序员作品。<br>
> BeautyEye工程参考和借鉴了来自互联网的大量素材，在此表示感谢。

## 最新版本
![](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/release_notes/v3.5_release_note.png)

> BeautyEye 起于2012年05月份，发布于2012年09月11日，最近一次版本发布是：2013年04月05日。

## 兼容性
BeautyEye 可运行于java 1.5、1.6以及1.7之上，但推荐至少应运行在[java1.6.0_12或更新的版本](http://www.java.com/zh_CN/download/) <br>([为何java1.6.0_10或u11版不行？](https://code.google.com/p/beautyeye/wiki/java_1_6_0_u10_BUG_6750920 ))，因为这些版本将能带来窗口透明特性，更重要的是Swing的性能提升。

另附：[BeautyEye兼容性测试结果](http://code.google.com/p/beautyeye/wiki/Compatibility_test_results).

## 主要特征
* 跨平台；
* 遵从主流审美，与时俱进；
* 更好的兼容性，可运行于java 1.5、1.6、1.7，SUN的非公开API被移除？木有关系；
* 源自Android GUI基础技术，以最少的代码实现最满意的外观，Synth、Nimbus都是浮云。

## 演示程序
<b>提示:</b> 请确保已安装JRE(最低java1.5版)，如需BeautyEye外观支持透明效果，则推荐java1.6.0\_12或更新版本<br>([为何java1.6.0_10或u11版不行？](https://code.google.com/p/beautyeye/wiki/java_1_6_0_u10_BUG_6750920))，这些版本才能支持窗口透明特性.

* [点击下载可执行jar包\(Swingsets2\)](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/demo/excute_jar/SwingSets2\(BeautyEyeLNFDemo\).jar)
* [点击下载可执行jar包\(Swingsets3\)](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/demo/excute_jar/swingset3_beautyeye.jar) <font color="#FF6600">\[推荐:thumbsup:\]</font>

## 下载方式
正式版.zip包：[点击下载](https://github.com/JackJiang2011/beautyeye/archive/3.5.zip)（内含demo、api文档、核心分发jar包等）.

## 开发指南
#### 第一步：引入*`beautyeye_lnf.jar`*包
核心分发jar包 *`beautyeye_lnf.jar`* 位于*“`/dist/`”*目录。

#### 第二步：在代码中使用BeautyEye
加入以下代码，即可将你的Java程序界面更换成BeautyEye的外观：
```Java
public static void main(String[] args)
{
    try
    {
        org.jb2011.lnf.beautyeye.BeautyEyeLNFHelper.launchBeautyEyeLNF();
    }
    catch(Exception e)
    {
        //TODO exception
    }
    ..................... 你的程序代码 .........................
    ..................... 你的程序代码 .........................
}
```

详细开发者指南请查看：[BeautyEye L&F简明开发者指南](http://code.google.com/p/beautyeye/wiki/Introduction).

## 授权方式
你可永久免费且自由地使用BeautyEye外观(look and feel)，如：用于研究、学习、甚至商业用途，但禁止在超越License约束内容的情况下用于商业用途等，请尊重知识产权。

## 联系方式
* 如有bug及建议等，请邮件至：`jb2011@163.com`；</li>
* 欢迎加入Java Swing爱好者讨论QQ群：`259448663`  <a target="_blank" href="http://shang.qq.com/wpa/qunwpa?idkey=9971fb1d1845edc87bdec92ad03f329c1d1f280b1cfe73b6d03c13b0f7f8aba1"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="Java Swing技术交流" title="Java Swing技术交流"></a>；
* 如需有偿提供应用软件整体或局部美化、方案制作、编码实现等，请联系作者QQ：`413980957`；
* 你也可前往 [Jack Jiang的微博](http://t.qq.com/jackjiang_is_here/) 进行交流。

## 关于作者
![](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/screenshots/js2.png)<br>
计算机科学与技术本科毕业，现正从业于移动互联网和智能穿戴应用领域；<br>
> <b>职业生涯：</b>程序员、项目经理、技术总监；<br>
> <b>编码技能：</b>JavaME、JavaSE、JavaEE、Android、iOS等平台应用层开发；<br>
> <b>实践经验：</b>多年的软件开发、项目管理、团队管理以及创业公司操盘经历，在软件开发体系和团队建设、项目开发和管理、中大型企业应用、移动互联网应用的持续开发/实施/集成/运维和信息化建设等方面拥有较丰富的实践经验，技术领域涉及传统企业桌面应用、企业分布式互联网应用、新一代移动互联网应用等。

## 特性预览
#### Part 1/2：[点击查看清晰原图](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/preview/be_lnf_preview.png)
![](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/preview/be_lnf_preview.png)

#### Part 2/2：[点击查看清晰原图](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/preview/be_lnf_preview2.png)
![](https://raw.githubusercontent.com/JackJiang2011/beautyeye/master/preview/be_lnf_preview2.png)

## 更多截屏
[Click here](http://code.google.com/p/beautyeye/wiki/screenshots_all_in_one)
