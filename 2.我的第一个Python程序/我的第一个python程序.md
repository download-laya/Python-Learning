# 2.我的第一个Python程序

## 2.1 前言

俗话说的好：工欲善其事，必先利其器。同样，你没有一个好的编辑器，你咋编程？IDLE就是Python自带的编辑器，当然，这节课我们就来学习如何使用IDLE。以及在IDLE中编写你的第一个Python程序！

在上一次，我们学习了如何在命令行中打开Python，这一次，我们来学习如何使用在Python下载之后自带的IDLE运行你的第一个Python程序。

## 2.2 打开IDLE

要使用IDLE，那就得先打开IDLE，你不打开IDLE你凭空想象一个“IDLE”啊？相信有些细心的小伙伴看见了开始菜单中添加了一个文件夹，叫做“Python 3.8”，没错，IDLE就在这！

点击文件夹，打开“IDLE (Python 3.8 64-bit)”，如果你看见了类似于这样的文本，恭喜你，你已经打开了IDLE！

```
Python 3.8.5 (tags/v3.8.5:580fbb0, Jul 20 2020, 15:57:54) [MSC v.1924 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
```

*~~（这图标谁画的，这么难看）~~*

好的，你现在已经成功进入IDLE了！
目标达成！
## 2.3 我的第一个Python程序

打开了IDLE之后，有的小盆友可能会问，这除了外观整体是白色，不就和cmd（命令行）一样吗？别着急，虽然它不能一下执行多行代码，但是我们调整调整就行啦。

首先点击File，又点击New File，当然，也可以按下快捷键ctrl+n，这样就新建了一个Python文件，二话不说

现在我们就可以写入代码了，但是有一个非常宇宙无敌的前提，就是：

CTRL+S保存！

CTRL+S保存！

CTRL+S保存！

保存之后就可以开始写代码了，我们在文件里写入：

```python
print('hello python world!')
```

让我们改装一下代码：
```python
world = "Hello Python World!"
print(world)
```
随后再保存一下，成功！

但是，我们咋运行呢？我们这时就要点击窗口上方的“Run”，点击“Run Module”就可以了。

如果你在窗口里看到了这样的字样：“Hello Python World!”恭喜你，你的程序编写成功了！
