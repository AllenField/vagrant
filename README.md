最近接触到新项目，短时间内学习了大量的东西，如果不记下来肯定全忘记了。
所以，关于vagrant的部分，我打算把官网的介绍翻译一遍就记在这里了。有不对的地方希望大家指证。

# Vagrant文档
Vagrant 一个用于管理虚拟机生命周期的命令行程序。这里将从头到尾把vagrant的各个方面介绍一遍，会覆盖的尽可能详细。

## 为什么选用Vagrant
Vagrant提供了基于行业标准技术构建的，易于配置，可复制，便携的工作环境，并且一直经由同一个工作流程控制，最大程度的帮助你和你的团队提供生产力和灵活性。

为了实现这一点，Vagrant站在了巨人的肩膀上。机器的供给是基于VirtualBox,VMware,AWS,或者其他提供方的。然后，行业标准的配置工具，比如shell脚本,Chef或者Puppet能被用于自动安装配置机器上的软件。

### Vagrant怎样给你带来好处
如果你是一个开发者，Vagrant为你提供了一个一次性且一直不变的环境，这将使你摆脱依赖和依赖的相关配置，且不必牺牲任何你在工作中使用的工具。一旦你或者其他人创建了Vagrantfile，你只需要vagrant up，然后所有的东西都安装配置好了。你团队中的其他成员也通过这个文件创建他们的开发环境，所以不论你们是工作在Linux,Mac OS X或者Windows上，团队的成员都在相同的环境中运行代码，基于一份相同配置的依赖。和"在我电脑上是好的啊"说再见吧!

如果你是一个运维工程师，Vagrant为你提供了一个一次性的环境和一直不变的工作流程去开发测试基础设施的管理脚本。你可以通过本地的虚拟化技术VirtualBox或者VMware，来使用shell脚本，Chef cookbooks，Puppet modules快速的测试。然后，在远程的AWS或者RackSpace云上，使用相同的配置，相同的工作流程来测试这些脚本。丢掉你的回收EC2的脚本吧，停止应付多种机器的SSH提示符吧，开始使用Vagrant把正常的精神带到你人生里来。

如果你是一个设计师，Vagrant会把wep app需要的所有的东西设置好，让你能把精力集中在你最擅长的事情上：设计。一旦开发者配置了Vagrant，你就再也不需要担心怎么让app运行起来了。再也不需要打扰其他的开发者来帮你修复环境你就可以测试设计了。just检出代码，vagrant up，开始设计。

## 安装Vagrant

## 开始指南
