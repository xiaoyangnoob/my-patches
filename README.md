# mesa-patches
- **本仓库存放我的mesa补丁，基于MIT协议分发。**  
- **注意：请使用主线代码应用补丁。（2934e1f提交测试成功）**  
- **如果需要请求补丁更新，请提issue**  
---
## 如何使用？
1. 克隆代码仓库 (**你首先需要安装git！**)
- **主线**
```
git clone --depth=1 https://gitlab.freedesktop.org/mesa/mesa.git ./mesa-main/
cd ./mesa-main/
```
- **2934e1f**
```
git clone https://gitlab.freedesktop.org/mesa/mesa.git ./mesa-2934e1f/
cd ./mesa-2934e1f/
git checkout 2934e1fad52806b4904a22c037c564eba6e21c85
```
2. 应用补丁 (**确保你在mesa代码库根目录下！**)
`git apply /path/to/your/patch`
---
### 感谢
* [Termux Packages developers](https://github.com/termux/termux-packages "Termux Packages Github Repository")
* [XMeM](https://github.com/XMeM "XMeM Github")
* **JeezDizReez**
* **airidosas252**
* [alexvorxx](https://github.com/alexvorxx "alexvorxx Github")
---
好的，没有什么要讲的了。END喽！
