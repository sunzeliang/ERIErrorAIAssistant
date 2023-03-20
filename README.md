# ERIErrorAIAssistant
## 说明：
***仅个人学习使用***
## 介绍：
***双击Unity的ErrorLog，使用ChatGPT来对其进行纠错 (可用于策划，测试，程序对基础报错进行排查，快速定位)***
- - -
### 环境
+ Unity2019-2020 [Unity官方地址](https://unity.com/)
+ Visual Studio 
### 使用
+ 将 `ChatGPTMgr.cs` 和 `LogEditor.cs` 放入Unity项目中
+ key.txt中填写OpenAI的key
+ 添加 `CHATGPT_ERRORAIASSISTANT` 宏
- - -
### 功能
<details>
<summary>✔️ErrorLog回调</summary>
  
  - 获取到Unity面板ErrorLog的点击回调
</details>

<details>
<summary>✔️接入ChatGPT</summary>
  
  - 通过HttpWebRequest来请求ChatGPT
  - 多线程请求
</details>


