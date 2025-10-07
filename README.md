# Comfyui-QwenPromptRewriter
Enhance your prompts using the Qwen LLM to align the behavior and capabilities of the Qwen-Image/Edit online version.  
**[[中文版本](./readme_zh.md)]**

## Preview
![](./img/preview.jpg)

## Usage
![](./img/nodes.png)  

- prompt\_style: `Qwen-Image_Edit` or `Qwen-Image` depending on your model.  
- llm\_model: For "Qwen-Image-Edit" style, please use the "qwen-vl-xxx" series model.    
- max\_retries: Maximum number of retries when an API call fails.  
- API\_KEY: Your [aliyun](https://www.aliyun.com/product/bailian) api key.  
- skip\_rewrite: Don't rewrite the prompt word, just output it directly.  

>  It is recommended to write your API_KEY into the `api_key.txt` file so you can share your workflow safely!
