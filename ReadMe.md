## 大模型测试

#### 下载
```shell
ollama run modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf

# （可选的，复制模型为较短的新名称并移除原名称模型）
# ollama cp modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf Qwen2.5:7B
# ollama rm modelscope2ollama-registry.azurewebsites.net/qwen/Qwen2.5-7B-Instruct-gguf
# ollama run Qwen2.5:7B
```
### DeepSeek-R1-Distill-Qwen 系列(不支持tools)
#### DeepSeek-R1-Distill-Qwen-1.5B-GGUF
```shell
ollama pull modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-1.5B-GGUF
ollama cp modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-1.5B-GGUF    DeepSeek-R1-Distill-Qwen-1.5B-GGUF
ollama run DeepSeek-R1-Distill-Qwen-1.5B-GGUF
```

#### DeepSeek-R1-Distill-Qwen-14B-GGUF
```shell
ollama pull modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-14B-GGUF
ollama cp modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-14B-GGUF    DeepSeek-R1-Distill-Qwen-14B-GGUF
ollama run DeepSeek-R1-Distill-Qwen-14B-GGUF
```

#### DeepSeek-R1-Distill-Qwen-32B-GGUF
```shell
ollama pull modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-32B-GGUF
ollama cp modelscope2ollama-registry.azurewebsites.net/unsloth/DeepSeek-R1-Distill-Qwen-32B-GGUF    DeepSeek-R1-Distill-Qwen-32B-GGUF
ollama run DeepSeek-R1-Distill-Qwen-32B-GGUF
```