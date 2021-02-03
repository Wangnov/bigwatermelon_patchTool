# 合成大西瓜素材替换工具
bigwatermelon_patchTool

这是一个带有**图形界面**的程序，可以替换**合成大西瓜**小游戏中的图片素材和标题名称。
A **GUI** tool that can replace the image material and game title in the **big watermelon** game

> 感谢[liyupi](https://github.com/liyupi/daxigua)的项目提供思路

### 操作步骤

 1. [下载](https://pan.baidu.com/s/1-VrDa5h94YymE8sDna1zkQ)替换工具（提取码：**xx66**。不含源代码，源代码请自行下载）
 2. 使用工具替换素材或修改标题
 3. 使用工具生成游戏资源文件（resource）
 4. 上传游戏资源文件

## Q&A

 - 我需要什么样的图片才可以完美替换为游戏中的水果？
 
 格式为**PNG**或**JPG**，图片非透明区域形状近似于**正方形**或**圆形**的图片。**图片保存的路径中必须不能存在中文！如果存在中文则会替换失败（正在修复）**例如，微信头像图片。你无需在意图片的像素大小，程序会自动调整。但如果你的图片形状不满足要求，则程序会拉伸图片导致略微变形。如需满足要求，可以使用任何图像处理手段裁剪图片，例如微信的图片编辑功能可以较好地裁剪。
 
 - 为什么我的背景图被拉伸的很严重？
 
 背景图的形状要求近似为**720*1080**（长宽比：3比2）的竖版长方形，如果长宽比相差过大则会导致拉伸变形严重。建议最好裁剪至合适的像素大小。
 
 - 如何上传游戏资源文件？

这里推荐使用腾讯云静态解析，优点在于免费、操作便捷、不易被微信封锁链接。缺点在于需要申请步骤较多、如果无已备案的域名，无法绑定域名。其他方法请参照[liyupi](https://github.com/liyupi/daxigua)的项目中提供的办法。此处提供使用腾讯云静态解析的操作步骤：

 1. 进入[腾讯云开发静态解析](https://cloud.tencent.com/product/wh)，通过微信扫码登录，选择注册新账号，扫码关注腾讯云助手
 2. 完成实名认证（行业、通讯地址可简写，填写完成后微信扫码、QQ扫码、人脸识别均可完成认证）
 3. 再次进入[腾讯云开发静态解析](https://cloud.tencent.com/product/wh)，点击开始使用
 4. 填写云开发环境名称（按规范填写，例如我起名为bigwatermelon）、下一步、下一步、同意授权（微信扫码认证）。等待1-3分钟，让环境初始化，初始化完成后点击环境名称进入环境
 5. 在左侧侧边栏中选择静态网站托管，点击开通，等待约3分钟的初始化（**如果觉得超过三分钟还没完成，点击刷新网页试试看**）
 6. 点击【上传文件夹】，上传小程序生成的游戏资源文件夹。文件夹可以改成自己喜欢的名字，但注意**最好只使用英文，不要使用标点符号（否则找不到游戏网址不要怪我）**
 7. 复制网页中的【默认域名】（例如我的默认域名近似为：bigwatermelon-1R53fdsfij34234534e-1242523452.tcloudbaseapp.com，也可以点击链接后面的复制按钮），在后面加上/resource（**如果你在上一步中修改了上传的资源文件夹名，则需要将resource改为你修改的名字**）
 8. 将**添加过/resource的链接**复制到任何浏览器打开，或发给你的微信好友，Enjoy it
