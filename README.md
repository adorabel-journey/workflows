# TODO

## CI 
~~- [ ] 从 comfyui 的 save Img 功能出，每次更新了json可以直接导出对应的img
为了方便直接看到工作流的样子和效果，也可以直接拖拽，并且保留了参数的。~~ 
(使用[comfyui-browser](https://github.com/talesofai/comfyui-browser)进行订阅同步) 

## 下载总成
三个LORA，一个VAE，两个ControlNet, 可能的两个插件

### 模型准备
lcm-lora-sdv1-5 https://huggingface.co/latent-consistency/lcm-lora-sdv1-5/tree/main
control modules https://huggingface.co/webui/ControlNet-modules-safetensors/tree/main (这里面包括可能缺失的canny,openpose,不过这里面都是fp16的)

### 插件准备 
- comfyui-job-iterato
- rembg相关的