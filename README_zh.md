# Comfyui-QwenPromptRewriter
使用千问大模型对提示词进行重写, 以对齐 Qwen-Image/Edit 在线版的效果和能力.  
**[[English version](./readme.md)]**

## 效果演示
![](./img/preview.jpg)

## 使用方法
![](./img/nodes.png)  

- prompt\_style: 根据你使用的生图模型选择`Qwen-Image_Edit`或`Qwen-Image`  
- llm\_model: 使用`Qwen-Image-Edit`模式时请选择`qwen-vl-xxx`系列模型.    
- max\_retries: API 调用失败时的最大重试次数.  
- API\_KEY: 你的 [阿里云](https://www.aliyun.com/product/bailian) api key.  
- skip\_rewrite: 不使用 API 进行提示词重写, 直接将提示词输出  

> 强烈建议将你的 API_KEY 写入本项目附带的 `api_key.txt` 文件中以便于安全的分享工作流而不会泄漏你的 Key
