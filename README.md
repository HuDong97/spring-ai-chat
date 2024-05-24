
本项目使用springAi调用openAi接口，目前可以使用chatGPT3.5,由于apikey原因并未上传配置文件
配置文件信息如下：
目前其他低版本项目或者微服务项目可以使用openfeign来调用该项目方法整合chatGpt到自己项目中

目前仅包含AI文字聊天，未来整合Ai图片上传分析

server:
port: 28080

spring:
application:
name: spring-ai-chat

ai:
openai:
api-key: sk-bToZitPEA******（可以在淘宝购买）
base-url: https://api.openai.com/
chat:
options:
model: gpt-3.5-turbo
temperature: 0.3F


