## 2020/11/12

入职第一天,全都是新面貌新气象.

- 配置环境,接到的第一个任务是介绍直播和互动

梳理直播和互动的技术,写的太杂,自己不太满意,
到了晚上9点才发现写了30多页,太零碎太杂没有整体感.

## 2020/11/13

入职第二天,上午修改了大纲,和领导沟通了一下大纲,还需要将各种术语进行解释.

近期有两个事:

- 腾讯云的试用和概念统一
- webrtc spec的继续推进(这个花时多,但意义重大)
- pion的webrtc/ion源码需要阅读了(这个可以在下班之后进行)

## 2020/11/14-2020/11/15

周末在家当咸鱼

## 2020/11/16-2020/11/20

一周时间,主要是梳理直播互动的技术,最后整理一个ppt文档.
期间协助处理啸叫问题,在添加腾讯sdk的3个参数后,有一些效果.

## 2020/11/21-2020/11/22

周末,陪孩子过生日,当咸鱼

## 2020/11/23

周一,上午讨论直播互动技术,下午到合肥面对面沟通

## 2020/11/24

周二,啸叫问题,确定腾讯sdk的效果不够,准备使用chrome+pion来传递音频数据,
主要解决的问题是将opus转成pcm,到晚上还是发现输出的pcm不正常.

下午5点开始讨论ppt,说实话,效果不理想,ppt都没翻完,主要是受众都是高管或应用层开发者,
这些底层的细节很难去沟通.

## 2020/11/25

周三,上午解决了输出pcm异常的问题,等后面的联调.

开始梳理spec和pion的源码阅读要开始.

下午按vad检测的思路去解决啸叫问题,但vad模块集成有问题.

## 2020/11/26

周四,按vad检测的思路去解决啸叫问题,验证可行性.(vad不能完全解决).

确认如何能解决这个啸叫问题,腾讯/研究院,(没什么具体的结论).