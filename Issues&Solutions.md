# 在这里存放部分目前已知的问题和解决方案，欢迎Pull Request！

1. issue: NekoBox 和 V2RayNG 等手机客户端无法连接使用，报错：Get "http://cp.cloudflare.com/" : websocket close 1005 (no status)

   solution: 在设置中打开FakeDNS（解决无法连接使用问题），测试地址改为 https://cp.cloudflare.com/（Cloudflare的这个地址要启用TLS，不然无法测速）或者任意地址（如 https://www.google.com/）
   
3. issue: Cloudflare 配置中的UUID报错

   solution: 使用标准的UUID V4，不知道的话就用V2RayN生成一个
