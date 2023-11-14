# 基于LSPosed框架的运动模拟器使用教程

# 本教程仅供学习交流，请勿用于非法用途！！！

**LSPosed仓库地址：[LSPosed/LSPosed: LSPosed Framework (github.com)](https://github.com/LSPosed/LSPosed)**

**LSPatch仓库地址：[LSPosed/LSPatch: LSPatch: A non-root Xposed framework extending from LSPosed (github.com)](https://github.com/LSPosed/LSPatch)**

**运动模拟器仓库地址：[Releases · zhufucdev/MotionEmulator (github.com)](https://github.com/zhufucdev/MotionEmulator)**

**运动模拟器Websocket插件仓库地址：[Xposed-Modules-Repo/com.zhufucdev.ws_plugin: Motion Emulator Websocket Plugin (github.com)](https://github.com/Xposed-Modules-Repo/com.zhufucdev.ws_plugin/tree/main)**

## 第一步：下载（链接：[Release relsease · Envystar/BetterRunning (github.com)](https://github.com/Envystar/BetterRunning/releases/tag/release)）

1. **下资源包，并解压安装所有apk(需先卸载创高体育)**

<img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\6fd3a1d9492560e875e121c4b2e1be47.jpg" alt="6fd3a1d9492560e875e121c4b2e1be47" style="zoom:50%;" />

## 第二步：登录

1. **打开创高体育，并登录账号（如果无法启动，则先启动LSPatch再尝试）**

## 第三步：打开LSPatch

1. **打开LSPatch，找到管理选项，检查是否有创高体育和Websocket模块，如图**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\8e30505a92c0a7e200ac83664a900d78.jpg" alt="8e30505a92c0a7e200ac83664a900d78" style="zoom: 25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\c8cf65ba093962417fef7930d0ae67a5.jpg" alt="c8cf65ba093962417fef7930d0ae67a5" style="zoom:25%;" />

2. **点击创高体育，找到模块作用域，勾选”运动模拟器Websocket插件“，并确认（必须登录之后再勾选，否则无法登录）**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\0aea4ab1b5eb08a0c614ccdb63a9bc9c.jpg" alt="0aea4ab1b5eb08a0c614ccdb63a9bc9c" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\2d099a0ee59af76445ed1a84f7dc34c9.jpg" alt="2d099a0ee59af76445ed1a84f7dc34c9" style="zoom:25%;" />

## 第四步：打开运动模拟器

1. **点击插件选项，进入后把”运动模拟器Websocket插件“拖动到启用区**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\fc57daa851ec7f5152bbdcda72847f3a.jpg" alt="fc57daa851ec7f5152bbdcda72847f3a" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\8cbe0a6c36c898322df316eab8719eae.jpg" alt="8cbe0a6c36c898322df316eab8719eae" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\a3bcf409b22c08b171a91de6ea5148da.jpg" alt="a3bcf409b22c08b171a91de6ea5148da" style="zoom:25%;" />

2. **点击记录选项，进入后点击继续（若应用申请运动权限，点击允许），进入后拿起手机模拟跑姿（摇两下手机即可）**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\0dbf20544a914163c09751323729a811.jpg" alt="0dbf20544a914163c09751323729a811" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\a7a5aae18670c532739d5db7abe84e2f.jpg" alt="a7a5aae18670c532739d5db7abe84e2f" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\c4dcfe746748681d42b77fdbb1bdea50.jpg" alt="c4dcfe746748681d42b77fdbb1bdea50" style="zoom:25%;" />

3. **点击绘制路径选项，进入后选择高德地图，绘制想要模拟的路径，然后保存**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\2c53ae10cc969becf4508f725de9597d.jpg" alt="2c53ae10cc969becf4508f725de9597d" style="zoom:25%;" />

4. **点击管理选项，找到路径选项，找到要模拟的路径，进入后把坐标系统改为WGS84（实测WGJ02有位置偏差）**

   **注：不要添加随机因子，不然可能无法模拟**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\2e9bfb5c495db33328a094b7b7c607be.jpg" alt="2e9bfb5c495db33328a094b7b7c607be" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\b7e42156e907cf7a28661c0f5a862787.jpg" alt="b7e42156e907cf7a28661c0f5a862787" style="zoom:25%;" />

5. **点击模拟选项，选择之前记录过的数据，选择想要模拟的速度（卫星数量不用动）**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\30bf8bbcb38fed9e790b23c12e4f198e.jpg" alt="30bf8bbcb38fed9e790b23c12e4f198e" style="zoom:25%;" />

6. **点击开始模拟按钮，进入后，打开运动软件，开始运动（这里效果图用keep测试）**

   <img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\c369b057746164575189fe023116733d.jpg" alt="c369b057746164575189fe023116733d" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\e74876ec38c80734d6ff0e5e26fe7c3e.jpg" alt="e74876ec38c80734d6ff0e5e26fe7c3e" style="zoom:25%;" /><img src="C:\Users\慕尘\Documents\Tencent Files\3331400783\nt_qq\nt_data\Pic\2023-11\Ori\89d342b7529ceca9b586958acd8fd8a2.jpg" alt="89d342b7529ceca9b586958acd8fd8a2" style="zoom:25%;" />