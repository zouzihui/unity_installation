# unity_installation
## Unity安装过程
**安装Unity3d开发平台**
* 安装UnitySetup64-5.6.2f1
![unitysetup](https://images.gitee.com/uploads/images/2020/0323/223910_3fa1575f_1648195.png "c9976676f158b4f55b71f6a17076c29.png")
* 安装UnityStandardAssetsSetup-5.6.2f1
![standarad](https://images.gitee.com/uploads/images/2020/0323/223934_68a1263f_1648195.png "e4af10da344a1dfe63fd30e70af6cd2.png")
* 安装UnitySetup-Android-Support-for-Editor-5.6.2fl.exe
![Android](https://images.gitee.com/uploads/images/2020/0323/223957_5914a7b6_1648195.png "816e2257660cc0d5c830ee6ac080473.png")

**安装Java开发平台**
* 双击安装包，点击下一步
* 路径改成D盘jdk1.8，点击下一步
* 出现弹框，点击确定
* 目标文件夹不用修改，点击下一步
* 安装完成

* 我的电脑→属性→高级系统设置→环境变量
* “用户变量”框中新建"JAVA_HOME"，变量值"D:\jdk1.8"
![JAVA_HOME](https://images.gitee.com/uploads/images/2020/0323/224148_345bb7d8_1648195.png "bd515fd6264e42669ce611a53e0b5ae.png")
* 编辑原有变量"PATH",在原值后加"%JAVA_HOME%\bin"
![path1](https://images.gitee.com/uploads/images/2020/0323/224216_364781c8_1648195.png "af70ccd96ebfe1e6fa36c627549d412.png")
![path2](https://images.gitee.com/uploads/images/2020/0323/224231_dfbef98b_1648195.png "c487ed24a1a16d7c8b20f01042673e2.png")
* 打开cmd,输入java，出现下图输出
![java](https://images.gitee.com/uploads/images/2020/0323/224442_b28c2369_1648195.png "65b9640d5746e41f66577c7ccf59ca4.png")
* 输入"java -version"，出现下图输出表明安装成功
![java -version](https://images.gitee.com/uploads/images/2020/0323/224506_e7e6fe01_1648195.png "42721e5dfbaf87d8569d5a97dced8bc.png")
* 输入"javac"，如此阿土证明环境变量配置成功
![javac](https://images.gitee.com/uploads/images/2020/0323/224523_e4a7d876_1648195.png "990c65bc9f49371179d76a45b53c9d4.png")

**安装Android开发平台**
* 安装sdk开发包
* 安装后点击"SDK Manager.exe"更新包
![更新](https://images.gitee.com/uploads/images/2020/0323/224545_c89a9926_1648195.png "410191f93dd216f40e5fea2c3273ec1.png")
* 启动unity(进入前需要注册用户)
* 点击"edit"→"preferences"→"Editonal Tools"→更改SDK路径"D:\android-sdk-wimdows"→"更改JDK路径"D:\jdk1.8"
* 新建场景→导入炸弹人游戏包→保存场景→点击"build setting"→选择"Android平台"→点击"Add Open Scenes"并选中保存场景文件→点击"Player settings"将"Other setting"中"package name"改为"com.zoe.sj"→点击"build"打包就完成了，生成apk文件
![apk文件](https://images.gitee.com/uploads/images/2020/0323/224946_f5cb3fad_1648195.png "735eb952187fa39c79b86cbfd000e74.png")
