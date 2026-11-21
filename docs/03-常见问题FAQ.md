# ❓ 常见问题 FAQ

> 20+ 高频问题解答，按类别整理

---

## 购买相关

<details>
<summary><b>Q1: 机场会不会突然跑路？</b></summary>

有可能。这是这个行业的固有风险。降低风险的方法：
- 优先选老牌机场，不要一次性买太长周期
- 不要充大额余额
- 准备 2-3 个备用机场
- 关注机场的 Telegram 公告群
</details>

<details>
<summary><b>Q2: 月付、季付、年付怎么选？</b></summary>

新手一律建议**先月付**。用稳定了再考虑长周期（通常年付有折扣）。但记住：周期越长，跑路风险敞口越大。
</details>

<details>
<summary><b>Q3: 免费试用靠谱吗？</b></summary>

靠谱的机场常提供 1-5GB 免费试用，用来测试速度。但要注意：
- 免费流量用完别指望继续白嫖
- 有些"永久免费"服务不稳定或有隐私风险
- 试用是用来判断质量的，不是长期方案
</details>

<details>
<summary><b>Q4: 支持哪些支付方式？</b></summary>

常见的有支付宝、微信支付、USDT（加密货币）。部分机场对支付方式有折扣差异。
</details>

---

## 技术相关

<details>
<summary><b>Q5: 导入订阅后没有节点怎么办？</b></summary>

1. 确认订阅链接完整无误
2. 检查账号是否到期、流量是否用完
3. 在客户端里手动点「更新订阅」
4. 换一个客户端试试（有时是客户端兼容问题）
5. 联系机场客服
</details>

<details>
<summary><b>Q6: 节点显示可用但实际连不上？</b></summary>

- 换一个节点试试（同一机场不同节点差异很大）
- 切换协议类型（如从 SS 换到 Trojan）
- 检查是否是本地网络限制（如公司/校园网）
- 晚高峰拥堵时容易失败，错峰试试
</details>

<details>
<summary><b>Q7: 速度慢怎么办？</b></summary>

1. 换节点 —— 不同节点速度差异极大
2. 换线路 —— 优先试专线/中转节点
3. 检查套餐是否有限速或倍率
4. 换客户端
5. 错峰使用（晚高峰普遍变慢）
</details>

<details>
<summary><b>Q8: 什么是倍率？0.5倍和2倍什么意思？</b></summary>

倍率影响流量消耗计算。0.5 倍表示用 1GB 流量只算 0.5GB（划算），2 倍表示用 1GB 算 2GB（不划算）。有些节点的特殊功能（如流媒体解锁）会有倍率。
</details>

<details>
<summary><b>Q9: 规则模式和全局模式怎么选？</b></summary>

日常用**规则模式**（智能分流，国内直连国外代理）。只有排查问题时才用全局模式。规则模式更省流量、速度更好。
</details>

<details>
<summary><b>Q10: 可以同时用多个机场吗？</b></summary>

可以。多数客户端支持导入多个订阅，在节点列表里切换。这也是"备用机场"的正确打开方式。
</details>

---

## 安全与隐私

<details>
<summary><b>Q11: 机场会看到我的浏览记录吗？</b></summary>

理论上，节点运营者能看到经过服务器的流量元数据。因此：
- 不要在不信任的免费节点上处理敏感信息
- 敏感操作叠加 HTTPS（现在绝大多数网站都是）
- 选择有隐私政策、口碑好的机场
</details>

<details>
<summary><b>Q12: 订阅链接泄露了怎么办？</b></summary>

立即到机场用户中心**重置订阅链接**，旧的会失效。不要把订阅链接发到公开场合（截图、群聊）。
</details>

<details>
<summary><b>Q13: 用机场合法吗？</b></summary>

这取决于你所在的地区和用途。请务必**遵守当地法律法规**。本仓库内容仅供学习研究参考，不构成任何使用建议。
</details>

---

## 设备相关

<details>
<summary><b>Q14: 手机和电脑能共用一个订阅吗？</b></summary>

看机场的"设备数限制"。有的限制 1-3 台，有的不限。不限设备数的机场在"特色系列"里有标注。
</details>

<details>
<summary><b>Q15: iPad 能用吗？</b></summary>

能。iPadOS 和 iOS 一样，用 Shadowrocket / Stash 等客户端。
</details>

<details>
<summary><b>Q16: 智能电视/电视盒子能用吗？</b></summary>

如果支持安装 Android 应用，可试试 Clash for Android；更简单的方案是在路由器上配置（见 [客户端配置教程](02-客户端配置教程.md) 路由器部分）。
</details>

---

## 进阶相关

<details>
<summary><b>Q17: 家宽节点是什么？有什么用？</b></summary>

家宽 = 家庭宽带 IP，相比机房 IP 更"干净"，被网站识别为真实家庭用户的概率更高，适合 AI 服务、银行、流媒体等场景。详见 [术语表](05-术语表.md)。
</details>

<details>
<summary><b>Q18: IEPL 和 IPLC 专线有什么区别？</b></summary>

都是跨境专线。IPLC 是传统国际专线，IEPL 是运营商的以太网专线，通常 IEPL 更灵活、部署更快。两者都比普通线路稳定。详见 [术语表](05-术语表.md)。
</details>

<details>
<summary><b>Q19: 流媒体解锁是什么？</b></summary>

指节点 IP 能正常访问 Netflix、Disney+、YouTube 等平台并解锁地区内容。不是所有节点都支持，选购时注意机场标注。
</details>

<details>
<summary><b>Q20: 为什么晚高峰变慢？</b></summary>

跨境带宽在晚高峰（约 20:00-23:00）拥堵，这是普遍现象。选专线机场、换低负载节点、错峰使用能缓解。
</details>

<details>
<summary><b>Q21: 如何测试一个机场好不好？</b></summary>

1. 买短周期套餐
2. 不同时段测速（早晚高峰各测）
3. 测试多个节点
4. 测试你实际要用的场景（看视频/AI/游戏）
5. 看客服响应速度
详见 [机场选购深度指南](04-机场选购深度指南.md)。
</details>

---

## 其他

<details>
<summary><b>Q22: 想推荐一个机场给你们，怎么操作？</b></summary>

欢迎到主仓库提交 Pull Request，按表格格式填写机场名称、链接、特点即可。我们会核实后合并。
</details>

<details>
<summary><b>Q23: 表格里的链接安全吗？</b></summary>

链接来自我们整理和社区提交，但仍建议：进入官网后核对域名、不要在不信任的页面输入密码。发现仿冒链接请提 Issue 反馈。
</details>

---

🏠 [返回文档首页](README.md) · 🌱 [新手入门](01-新手入门指南.md)

⭐ 觉得有用？给 [主仓库](https://github.com/jichangtuijian-vpn/JiChangTuiJian) 一个 Star 吧。
