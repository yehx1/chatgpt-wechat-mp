# chatgpt-wechat-mp
# 只需一步：微信公众号接入大模型
&nbsp;&nbsp;如何让微信公众号接入大模型文案创作能力，实现类似ChatGPT文案创作功能。方法其实很简单，只需打开地址“http://www.botaigc.cn:8900/mpauth”，用微信扫码即可给自己申请的公众号进行授权。    
&nbsp;&nbsp;下面将分以下4个部分进行介绍  
&nbsp;&nbsp;（1）扫码授权  
&nbsp;&nbsp;（2）使用方法  
&nbsp;&nbsp;（3）GPTs：指定角色  
&nbsp;&nbsp;（4）停用接口  
## 1、扫码授权  
&nbsp;&nbsp;微信公众号接入大模型文案创作能力的扫码地址为“http://www.botaigc.cn:8900/mpauth”，页面如下。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/c84e30ac-c873-46fb-b9f5-b436ac3f7ed4)
&nbsp;&nbsp;点击授权按钮弹出二维码，扫描授权后即可获得大模型文案创作能力。授权成功后，我们可以在微信公众号后台进行查看。微信公众号后台- -> 内容与互动 --> 自定义回复，显示“你已授权给RdFast智能创作帮助你运营公众号，点击管理已授权的第三方平台”。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/7550f35d-9a92-41c1-bb00-3d7647d9886c)
## 2、使用方法
### &nbsp;&nbsp;（1）输入问题
&nbsp;&nbsp;扫码完成后，任何公众号用户在公众号内输入问题即可获得大模型创作结果。如下所示，输入“请以公众号快速接入大模型写一段推广用语”。由于公众号不能实时返回结果，所以需要等待全部结果输出之后，才可以返回。通常每秒创作10个字或几十个字，因而文案创作结果内容越长，则所需等待时间越久。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/e2957c85-cb4b-4653-b024-06b083f91729)
### &nbsp;&nbsp;（2）获取创作结果  
&nbsp;&nbsp;在等待一段时间后，可以输入任意内容获取返回结果，比如输入“1”。如下图所示。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/2ae15043-ffab-4919-b329-2d6491a74958)
### &nbsp;&nbsp;（3）强制重新开始  
&nbsp;&nbsp;如果几分钟过去了，仍然无法获取到创作结果，那么可以通过输入“rdfast”来进行重置。重新进入到创作状态，这时候需要输入新的问题，之前输入内容则已经无效。  
### &nbsp;&nbsp;（4）清空历史  
&nbsp;&nbsp; 正常创作过程会结合历史上下文内容，输入“清空历史”后，下次对话将不考虑之前的历史信息，这相当于开始了一个新的会话。  
## 3、GPTs：指定角色  
&nbsp;&nbsp;指定角色是指可以假定大模型文案创作系统为特定的角色。设置规则为：  
&nbsp;&nbsp;“系统属性设置：xxxx”  
&nbsp;&nbsp;例如：“系统属性设置：翻译助手”，从而达到类似GPTs的功能。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/68dc8238-3a40-4fe4-b90b-4d364e434dcd)
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/14b1d738-c93b-4224-9487-4f6de5fc0103)
## 4、停用接口  
&nbsp;&nbsp;停用大模型创作接口如下所示：  
&nbsp;&nbsp; 微信公众号后台 --> 设置与开发 --> 公众号设置 --> 授权管理 --> 查看平台详情 -- > 取消授权。  
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/afd66480-4069-4d19-a4d5-c29ab29f33e8)
![image](https://github.com/yehx1/chatgpt-wechat-mp/assets/27985664/0058a87e-b0d2-4ed7-aa20-29988ba4af4f)

