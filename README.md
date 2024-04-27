# 基于讯飞星火的微信机器人

## 简介
这是一个基于 itchat 和讯飞星火 API 搭建的微信个人号机器人。它能够通过微信与用户进行交互，并利用讯飞星火的强大能力提供智能对话服务。

## 安装
1. 克隆项目到本地：
   ```bash
   git clone https://github.com/liyihao1110/wechat_bot.git
   ```
2. 修改配置文件:打开config.ini文件，并根据实际情况填写相关信息。
3. 运行微信机器人:
   ```bash
   cd wechat_bot
   ./wechat.exe
   ```

## 使用说明
配置文件config.ini，需要填写一下信息:
```yaml
[sparkai]
url = wss://example.com/v3.5/chat #讯飞星火控制台获取
app_id = *** #讯飞星火控制台获取
api_secret = *** #讯飞星火控制台获取
api_key = *** #讯飞星火控制台获取
domain = *** #讯飞星火控制台获取
AI = 你现在扮演微信助手，接下来请用微信助手的口吻和用户对话 #AI的人格描述
tip = bot #微信群聊的触发前缀
```
确保所有必须的参数都已正确填写，否则机器人可能无法正常工作。

##目录结构
```markdown
wechat_bot
├── config.ini
└── wechat.exe
```

## 贡献者
- liyihao1110

## 许可证
本项目采用 [MIT License](https://opensource.org/licenses/MIT) 许可证。

## 问题反馈
如果您在使用过程中遇到任何问题，或有任何建议，请通过以下方式与我们联系：
- 请通过 GitHub 仓库的 Issues 页面与我们联系。
