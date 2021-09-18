## helloakka

这是一个 scala+akka 开发的入门示例教程。使用 vscode 调试。

### 环境准备

- win10
- JavaSE-11
- scala-2.12
- sbt

- vscode 扩展:
    - Scala Syntax (official)
    - Scala (sbt)
    - Scala Extension Pack
        VS Code extentions to boost Scala developers

只有安装了 Scala Extension Pack, 才能在 VSCode 中断点调试 scala.

### 创建一个项目

项目的脚手架从下面链接获取，项目类型选择 scala，其他默认。本项目也是完全取自 akka-quickstart-scala.zip。

    https://developer.lightbend.com/start/


在文件 AkkaQuickstart.scala 的函数中第一行放置断点，即可按 F5 调试：

object AkkaQuickstart extends App {
>>    val greeterMain: ActorSystem .......

}
