# Linux 安装与设置

## 32位与64位版本的取舍

基于性能、稳定性以及硬件成本的综合考虑，我们优先推荐使用64位的Linux发行版，同时建议将个人电脑的内存升级到至少4G以上。

本设置指南全部基于64位Linux发行版进行编写。

## 独立显卡与集成显卡

电脑中所安装的独立显卡经常会造成严重的兼容性问题，甚至导致操作系统不可使用，可采取以下几种办法尝试解决：

- 在主板BIOS设置中禁用独立显卡（只有部分BIOS支持该功能）
- 在Linux发行版自带的软件源中寻找并安装独立显卡驱动，并测试运行效果（导致操作系统不可用的风险较高）
- 下载官方闭源独立显卡驱动，根据说明安装并测试运行效果（导致操作系统不可用的风险极高）
- 更换不同的Linux发行版，测试独立显卡运行时的效果（不同Linux发行版所使用的图形化操作界面有区别，所以对不同图形硬件的兼容性和运行效果也不同）

## Linux 发行版选择

由于Linux的各个发行版差异较大，经过反复测试和使用经验，推荐根据个人电脑实际表现测试安装以下两种Linux发行版，并选择性能及稳定性最好的一个使用（根据大量的测试和实际使用结果，我们优先推荐使用 Linux Mint）：

- [Linux Mint 17.1](linuxmint.md)
- [Ubuntu 15.04](ubuntu.md)

另外，由于国产Linux发行版[Deepin](http://www.deepin.org/)在我们的测试和使用过程中有着非常优异的表现和极高的易用性，对于动手能力强并且有一定Linux经验的朋友也可考虑尝试使用：

- [Deepin 2014.3](deepin.md)
