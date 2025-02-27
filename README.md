# 欢迎使用陌光助理M-Assistant - 以下简称: MA.           
## By:大陌DM
# 交流群:647374483(资源下载)
# 作者QQ:269653764
## <高效搭建,高效调用>是MA的宗旨
![image](https://github.com/user-attachments/assets/ec28840f-ecbd-44c5-97bb-d682d4db4631)
这是一款Windows平台综合自动化软件,不管你会不会代码,都能调用丰富的命令完成任务,
陌光助理结合当下全球第一热门的Python语言,内置有完整的解释器,能在异机完美运行,
可迸发出全新的调用体验.集合丰富的常用功能动作预设,可高效的搭建脚本,具有丰富的拓展性,
可以编辑出自己长期复用的动作,把你常用的py代码块都整合进MA当中,
灵活调度,不用再重复的写枯燥的代码,像拼接积木一样完成一个任务.

陌光助理M-Assistant 软件特色(天下武功,唯快不破):
0.高效的键鼠拾取,其他RPA还没启动完毕,MA早已拾取完毕.(比起录制更好微调)

1.动态的执行过程让你对任务的每个执行细节一目了然,执行与调试一体化.

2.强大的步骤编辑调试能力,参数编辑可视化,变量全局调用,各个动作可在底层联动.

3.丰富的动作拓展,灵活调度python代码块,不懂代码好用,懂代码的狂喜.

4.python代码块变量与陌光助理变量同步联动,灵活性&拓展性MAX.

5.无过多干扰页面与复杂的项目加载逻辑,让用户可专注创建动作,占用资源极小.

6.支持窗体后台操作,相对操作逻辑.

7.支持识别图像移动光标点击.

8.高效在多个动作链之间丝滑切换编辑,加载迅速.

9.上手极其简单,功能配置简单,随手随心即可创建工作流,.

10.完备的键鼠模拟,不仅限于108键!秒速hook抓取!行云流水的体验!(我就是觉得其他RPA新建几个动作都非常麻烦,人生苦短...我用MA)

为何要写这款软件? 某天我想录制个简单动作,打开某RPA,要联网登录,新建与切换个脚本项目..各种加
载等待,10%常用功能被混入到大量干扰动作里,虽然很丰富但想找个想用的功能过程属实很拖沓,

每个动作的创建都变得异常繁琐,我添加10个点击动作得打开10次对话框确认,emmmmmm....我觉得应该可以更快更方便更聚焦一些,所以心想做一款在功能与体量之间极佳平衡的软件,所以陌光助理M-Assistant应运而生,
雪藏HsFreezer的诞生就是减少等待焦虑用的,没错,MA也是秉持这个理念,让用户在与
创作中,尽可能的不被过多界面干扰,集中但不失强大,你想用的往往都有,没有的也能随心创造.
希望陌光助理能代替大陌为你战斗!
---------------------------------------------------------------------
Ps:大家如果有好的想法和建议,以及有各种使用中的问题(bug),请联系作者反馈.

# 使用说明
陌光助理M-Assistant 以下简称: MA.
只详细介绍一些比较不好理解的动作,简单顾名思义的动作就一笔带过啦,自行添加测试一下即可:

鼠标操作:可进行光标移动,点击,按下(拖拽),松开等.支持按键:<左键><中键><右键><X1><X2>

键盘操作:可支持完整的108键键盘按键动作(以及一些非键盘按键:如F13-F24等), 点击,按压,松开. 
光标相对位置动作: 获取光标位置,在光标位置的基础上执行相对偏移的移动,再根据上方选定的动作执行.

组合键:自行选中修饰符<ctrl,alt,shift,win等>+一个自定义按键组合成快捷键.

抓取操作:在指定位置用<光标妙抓>快捷键即可抓取.

其他动作:在参数里都有说明了,过后再做一期详细介绍视频.

实用小技巧:

0.<开启/中断任务>快捷键是MA的紧箍咒,方便打断任务.(ctrl+alt+del可以强制打断键鼠循环)

1.批量多选中动作后, 可以批量往选中的动作后  插入/粘贴其他任何动作.(批量延时等)

2.善用动作编辑栏的快捷键,让编辑变得十分高效.

3.用热键触发任务后,请尽快离手,因为某些键鼠动作会与还未松开的按键形成新组合键导致预期按键失效.
比如你按着ctrl+xxx作为快捷键触发的动作是带有点击键盘a的动作,就变成了ctrl+a,可以在动作链最前面加入0.3秒延时. (默认有0.2秒延时.)

4.对于无法键鼠输入的游戏或进程(DirectX输入屏蔽),可用远程软件间接操作.(但远程的画面有细微波动,识图可能会失效.)

5.字符串类赋值变量用花括号:{ } 取值传递,其他类型(list,dict等)直接输入变量名.

6.<??运行Python代码>不依赖于本机py环境,用的是内置解释器进行,你用该动作写的任何代码在异机上能正常运行.

7.双击动作编辑框,可对参数进行快速修改(但请严格遵循参数格式).

8.<复制可执行代码> 所得到的代码, 可在<??运行Python代码>动作中插入该代码,加入自己的复杂逻辑(只需掌握简单py语法,即可调用一切MA动作.)
例如 循环10次左键点击: 可以使用<??循环下一行N次>动作来实现,也弄通过自己组装实现:
for i in range(10): 
    执行([['??前台左键(绝对坐标)', '(750,680)']])
按照这个逻辑,你可以创建出各种各样的实用高级动作,MA具有无穷的拓展性,真正实现<高效搭建,高效调用>.

# <运行Python代码>内置联动参数与方法:

## 返回值("设置当前行返回值格")

## 备注("设置当前行备注格")

## msleep(1) #MA专用延时方法(秒),中断任务时,该延时会被直接打断跳过.

### stopflag  #运行任务时,该值为1, 终止任务时,该值为0,可通过此变量控制自编脚本开关


    举例: 
    
    while not stopflag:
        执行([['??前台左键(绝对坐标)', '(750,680)']])
        msleep(5)
    返回值("执行结束")
    
    这个循环可以被开关直接打断.
    也可以写成这样:
    
    while 1:
        执行([['??前台左键(绝对坐标)', '(750,680)']])
        msleep(5)
        if stopflag==1:
            返回值("执行结束")
            break
    
    但如果你这么写:
    while 1:
        xxxxxx()
        sleep(5)
        if xxxxx:
            break
    你这个线程跑起来就无法用开关打断,只能等待逻辑自动结束,如果是死循环,这条线程就出不来了.
