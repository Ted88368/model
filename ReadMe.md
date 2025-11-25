## 大模型测试

#### 下载
```shell
ollama run modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf


ollama pull modelscope2ollama-registry.azurewebsites.net/DeepSeek-R1-Distill-Qwen-1.5B-GGUF
ollama pull modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-14B-GGUF
ollama pull modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-32B-GGUF

# （可选的，复制模型为较短的新名称并移除原名称模型）
# ollama cp modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf Qwen2.5:7B
# ollama rm modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf
# ollama run Qwen2.5:7B
```