# gemini-proxy

### 食用方法：[https://zhile.io/2023/12/24/gemini-pro-proxy.html](https://zhile.io/2023/12/24/gemini-pro-proxy.html)

### Demo

```bash
curl \
  -H 'Content-Type: application/json' \
  -d '{"contents":[{"parts":[{"text":"Write a story about a magic backpack"}]}]}' \
  -X POST https://gemini.baipiao.io/v1beta/models/gemini-pro:generateContent?key=YOUR_API_KEY
```
