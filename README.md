# Ollama Server

简单封装的 Ollama server 服务。

用于兼容 OpenAI API 的 HTTP 访问。

```bash
# 进入 ollama-service 容器
docker exec -it ollama-service bash


# 下载模型
ollama pull qwen2
..

# 查看本地缓存的模型
ollama ls
NAME                                                    ID              SIZE    MODIFIED   
rjmalagon/gte-qwen2-1.5b-instruct-embed-f16:latest      90ba362f8207    3.6 GB  2 days ago
qwen2:72b                                               14066dfa503f    41 GB   3 days ago
yi:34b                                                  ff94bc7c1b7a    19 GB   3 days ago
quentinz/bge-large-zh-v1.5:latest                       bc8ca0995fcd    651 MB  3 days ago
qwen2:latest                                            e0d4e1163c58    4.4 GB  3 days ago
```