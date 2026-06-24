# 觅墨 MemoAI

本地 AI 笔记工具。支持 Ollama 本地模型离线使用，也支持 DeepSeek 云端 AI。

本地知识库、笔记加密、语义搜索、AI 对话，一个桌面应用全搞定。

### 功能

本地模型离线可用 · 云端 AI 随时切换 · SM4 隐私加密 · 语义搜索 · 一句话记笔记 · 晨曦黑夜双主题

### 下载

→ [最新版 DMG 下载](https://github.com/rainstormShi/MemoAI-Releases/releases/latest)

### 关键词

`笔记` `AI` `Ollama` `DeepSeek` `本地模型` `知识库` `隐私加密` `离线` `macOS` `桌面应用` `note-taking` `knowledge base` `personal AI` `local LLM`
# 觅墨

自己用的笔记 + AI 工具，记录下都做了什么。

- 接了两个 AI 后端，本地 Ollama 和云端 DeepSeek，在设置里随时切。
- 用本地模型的时候完全不用联网，断网环境一样跑。
- 笔记可以设密码，存的时候 SM4 加密，直接看文件是乱码。
- 布局是左侧笔记列表、右侧聊天区，聊到相关内容会自动关联已有笔记。
- 记笔记不用填表单，聊天框发 `存：xxxx`，自动提取标题标签摘要。
- 搜索笔记支持语义和时间，不是纯关键词匹配，模糊一点也能找到。
- 做了晨曦和黑夜两个主题，偏好记在 localStorage 里。
- 数据都在本地，笔记是 md 文件，放 `~/.memoai/` 下面。
- 桌面端用 pywebview 套的，macOS 原生窗框 + 内嵌 WebKit，不臃肿。
