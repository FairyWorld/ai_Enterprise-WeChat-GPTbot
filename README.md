# Enterprise-WeChat-GPTbot
基于企业微信外部群的微信机器人，支持FASTgpt
# 企业微信机器人使用教程：
1.打开项目下载企业微信4.0.8.6027版本 下载：https://drive.weixin.qq.com/s?k=ANMA2gc2ACsPG276C0

### 功能介绍：
记录活动: 这个机器人会记下它所做的所有事情，就像写日记一样，这样如果出了问题，可以回头查看它写的日记找出问题所在。
读取设置: 这个机器人在开始工作之前会查看一个叫做“config.ini”的文件，这个文件就像是它的指令手册，告诉它需要什么信息和规则来工作。
设置工作环境: 机器人为自己设置一个工作环境，这样它知道在什么情况下应该报告错误。
学习语言工具: 机器人会下载一些学习材料，以便更好地理解和处理人类的语言。
发送消息: 机器人有能力向某个地方（API）发送消息，并从那里得到答复，就像发短信给一个朋友并等待他的回复。
打开企业微信: 机器人会自动打开一个叫企业微信的程序，并等待你用账号登录。
处理聊天: 当机器人在企业微信中收到消息时，它会根据它的指令手册（config.ini文件）来决定如何回应，比如它可能只回应来自特定好友的消息。
检查消息长度: 如果收到的消息太长（超过200个字符），机器人会回复说消息太长了。
记住聊天内容: 机器人会记得和你聊天的内容，这样它可以根据之前的聊天回复，而不是每次都从头开始。
回复消息: 当机器人收到消息时，它会想出一个回复，然后发送给发消息的人。
保持警觉: 机器人会一直保持开启状态，随时准备接收和回复消息，除非你告诉它停止。

群管理配置：当自己在群发消息的时候还会脚本提示窗里有”r“开头的一串数字，这是群的id
![c19c0448b894ae36253c343ef82f9c2](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/983c4ed8-0eda-4e28-bf1c-243585e33764)

### 功能介绍：

[API]
api_key：这是您用来访问某些在线服务的密钥。例如，如果您的机器人使用在线AI服务来生成回复，您需要将其API密钥填写在这里。
app_id：如果API服务要求一个应用ID，可以在此填写。
[PrivateChat]
whitelist：您可以设置机器人只回复来自特定好友的消息。将好友的用户名或昵称以逗号分隔列出。如果您希望机器人回复所有好友的消息，请填写 all。
ad_signature：这是机器人在私聊消息中自动添加的签名或广告。例如，“回复由机器人提供”。
interactions_limit：设置机器人在私聊中每个对话的回复次数限制。
[GroupChat]
whitelist：您可以设置机器人只回复来自特定群组的消息。将群组ID以逗号分隔列出。如果您希望机器人回复所有群组的消息，请填写 all。
ad_signature：这是机器人在群聊消息中自动添加的签名或广告。例如，“回复由机器人提供”。
interactions_limit：设置机器人在群聊中每个对话的回复次数限制。
trigger_word：设置触发词，当群聊消息中包含此词时，机器人才会回复。
[Conversation]
use_common_conversation：设置是否在不同的对话中使用共同的对话历史。True 表示共享历史，False 表示每个对话有其独立的历史。


# 开始
2.配置，
打开https://aiwis.cn/网站，点击创建ai
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/49b7e76a-2908-4431-a9e1-26ceb1702ebb)
进入网站点击新建应用，点击生成key
![微信截图_20230703101749](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/2d4fbf96-879d-4c71-aae8-04e152616829)
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/bb9e7f3c-0e91-4cd2-ab2f-13d35a92b3e3)
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/a3987928-8271-4fd2-8b5f-c7af94360ecc)

# 交流群
![微信图片3445](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/c40ec040-dd93-48c3-b95e-53f9e9f23375)


大家好！我非常高兴地告诉大家，我已经成功完成了我的代码项目！通过不懈的努力和团队合作，我们成功实现了一个更智能的企业微信聊天机器人。

在这个过程中，我意识到为了进一步改进项目并提供更好的用户体验，我们需要一些资金支持。因此，我希望能够向大家征求赞助。这些资金将用于购买必要的资源、改进代码和增加功能，以确保我们能够提供最好的服务。

作为赞助者，您将享有以下特权和回报：

优先体验新功能和更新：您将成为第一个尝试和体验项目的最新功能和改进的人。
参与项目决策和功能讨论：您的声音和意见对项目的发展至关重要，您将被邀请参与项目的决策和功能讨论。
特别感谢和认可：作为项目的赞助者，您将得到我们的特别感谢和认可，您的支持将在项目中被特别提及。
如果您愿意支持我和我的项目，您可以通过以下方式进行赞助：

不管您是否能够提供赞助，我都非常感谢您对我项目的关注和支持。如果您有任何问题、建议或意见，也请随时与我交流。让我们一起为项目的成功努力！

谢谢大家！无论您是否能够赞助，您的支持对我来说都非常重要。让我们共同见证这个项目的成长和进步！
![1e466e5accd00e5851137bd45afca449](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/9148c9ec-6b13-42a7-a73c-9f8d75984d01)
