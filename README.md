## 简介
littleuck is a cross platform Java Swing LookAndFeel

## 功能介绍
* Translucent shadow window border
* LCD font for translucent window
* Flattening interphase support
* Suspension scrollbar for scrollpane
* Android ninepatch draw support
* Simple and easy extension
* Much more...

## 运行依赖
* JDK 8+ for littleluck

## 快速入门

Download littluck, Add it to you project.

`Startup.java`<br>

```Java

public class Startup
{
    public static void main(String[] args)
    {
        // if open it close
        System.setProperty("awt.useSystemAAFontSettings", "off");

        EventQueue.invokeLater(new Runnable()
        {
            public void run()
            {
                try
                {
                    LittleLuck.getSingleton().luanchLookAndFeel();
                }
                catch (Exception e)
                {
                    e.printStackTrace();
                }
            }
        }
    }
}

```

## 图片预览
![JButton](https://raw.githubusercontent.com/freeseawind/littleluck/master/screenshots/1.png)

![JProgressBar](https://raw.githubusercontent.com/freeseawind/littleluck/master/screenshots/6.png)

![Text](https://raw.githubusercontent.com/freeseawind/littleluck/master/screenshots/7.png)

![JToolip](https://raw.githubusercontent.com/freeseawind/littleluck/master/screenshots/8.png)

:point_right: [more](https://github.com/freeseawind/littleluck/wiki/Screenshots)

## 联系作者
* 如有Bug和建议邮箱至 :love_letter:  `iphonewang@foxmail.com`
* 欢迎加入Java技术讨论群 `148079860` <a target="_blank" href="http://shang.qq.com/wpa/qunwpa?idkey=1db134f79c4bcb759a21302f4243a88ffb20f8f7b6ae5e66c38bd5c02604aa27"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="Java 技术交流群" title="Java 技术交流群"></a>
