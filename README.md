# unity_installation
## Unity安装过程
**安装Unity3d开发平台**
* 安装UnitySetup64-5.6.2f1

* 安装UnityStandardAssetsSetup-5.6.2f1

* 安装UnitySetup-Android-Support-for-Editor-5.6.2fl.exe

**安装Java开发平台**
* 双击安装包，点击下一步
* 路径改成D盘jdk1.8，点击下一步
* 出现弹框，点击确定
* 目标文件夹不用修改，点击下一步
* 安装完成

* 我的电脑→属性→高级系统设置→环境变量
* “用户变量”框中新建"JAVA_HOME"，变量值"D:\jdk1.8"
* 编辑原有变量"PATH",在原值后加"%JAVA_HOME%\bin"

* 打开cmd,输入java，出现下图输出
* 输入"java -version"，出现下图输出表明安装成功
* 输入"javac"，如此阿土证明环境变量配置成功

**安装Android开发平台**
* 安装sdk开发包
* 安装后点击"SDK Manager.exe"更新包
* 启动unity(进入前需要注册用户)
* 点击"edit"→"preferences"→"Editonal Tools"→更改SDK路径"D:\android-sdk-wimdows"→"更改JDK路径"D:\jdk1.8"
* 新建场景→导入炸弹人游戏包→保存场景→点击"build setting"→选择"Android平台"→点击"Add Open Scenes"并选中保存场景文件→点击"Player settings"将"Other setting"中"package name"改为"com.zoe.sj"→点击"build"打包就完成了，生成apk文件


